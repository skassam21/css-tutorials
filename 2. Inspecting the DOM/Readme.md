# 1. Inspecting the DOM

When you don't know what the problem is with your HTML and CSS, your first step is the inspect the DOM! This should become your best friend as a frontend developer. 

## What is the DOM?

DOM stands for Document Object Model. When you inspect elements in your browser, you are inspecting the DOM. It looks identical to the HTML and CSS you have written in your files. However, there are a few differences. 

1. The DOM shows you how your browser has parsed your HTML and CSS. 

2. If you make changes to the DOM, it doesn't change your source code. It only changes what you see in your `browser`.

3. In the future, you will see how Javascript can manipulate the DOM. It doesn't manipulate your HTML and CSS. It manipulates what your browser has parsed from your HTML and CSS files. 

4. If you make a mistake in HTML (like missing ending tags, or not nesting elements properly), the browser will try to correct you. Those changes can be seen in the DOM. 

Want to learn more? See the following links:

- [What is the DOM?](https://css-tricks.com/dom/)
- [Intro to DOM](https://www.w3schools.com/js/js_htmldom.asp)

## How do you inspect the DOM?

Here are the steps to inspect the DOM:

1. Open up your website in a browser (preferably Chrome, Firefox or Safari, in that order). If you are using Safari, you may need to turn on [Developer tools](https://support.apple.com/en-ca/guide/safari/use-the-safari-develop-menu-sfri20948/mac).

2. Right click on an element, and hit the `Inspect` or `Inspect Element` option. This will open your Developer tools. 

3. Observe the HTML written in the `Elements` section, and the CSS written in the `Styles` section.