# CSS Box Model

All HTML elements are considered a box. The box consists of margin, borders, padding and content. 

By default, the width and height of an element is calculated like this:

- width + padding + border = actual width of an element
- height + padding + border = actual height of an element

Here is the default box model:



However, this is annoying because this means: When you set the width/height of an element, the element often appear bigger than you have set (because the element's border and padding are added to the element's specified width/height).

This can be fixed using the box-sizing property.

## Box-sizing Property

There are multiple different types of box models, which can be changed with the box-sizing property. A very useful one is `box-sizing: border-box;`. This is the model that Bootstrap uses. When you included bootstrap, you probably noticed that the size of elements changed. That is because `border-box` includes padding and border in the width and height. This is a very useful property.

# Sources

You can read more about the box model [here](https://www.w3schools.com/css/css_boxmodel.asp) and [here](https://www.w3schools.com/css/css3_box-sizing.asp).
