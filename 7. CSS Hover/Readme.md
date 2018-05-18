# CSS Hover

Showing new items on hover can be tricky in CSS, especially if you are using the `visibility` or `display` property. 

## Common Problems

1. If an object is `visibility: hidden;` or `display: none`, you cannot hover over it. So, using the hover property can be a bit tricky. 

2. Furthermore, if an object is underneath another object, you cannot hover over it either. Therefore you should try to use `z-index` to change its position, and make sure you are setting the `:hover` rule on the right element. 

You can look through the examples to get an idea of these problems. 
