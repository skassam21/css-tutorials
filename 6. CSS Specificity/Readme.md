# CSS Specificity

If you write some CSS and notice that nothing changed, and that the rule you wrote was crossed out when you inspected the DOM, that is because your CSS was being overrided by another rule. Here are a couple of notes about CSS Specificity:

## More important rules come afterwards 

If you wrote something like this:

```css

p {
	color: red;
}

p {
	color: blue;
}

```

The `p` tag would be color blue in the end, because whatever is written later on takes precedence. This is also applied across files, so always remember to put your own stylesheets after libraries (since you'd want to override some behaviour in libraries).

## More specific rules override less specific rules 


If you wrote something like this:

```css

p.class-1 {
	color: blue;
}

p {
	color: red;
}

```

Then for the element `<p class="class-1"></p>`, the color would be blue. That is because p.class-1 is a more specific rule, even thought it comes before the other rule in CSS.

## The !important rule

If you want to force a rule to override another rule, you can use the `!important` rule. However this is **NOT BEST PRACTICE**.

Example:

```css

p {
	color: red!important;
}

p {
	color: blue;
}

```

The text of the `p` element will be red. 


## Inline styles

Inline styles take precedence over other types of CSS (i.e. CSS written in an external sheet). However, using inline styles as well, is not best practice, but is good for debugging purposes.