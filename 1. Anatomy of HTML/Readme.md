# 1. Anatomy of HTML

Below is the basic structure of an HTML file. 

```html
<!DOCTYPE html>
<html>
	<head>
		<title>My Title</title>
		<meta charset="utf-8"/>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
	</head>
	<body>
		<!-- Page Content Goes Here -->
		<h1>Hello World</h1>
	</body>
</html>
```

Each individual part of the file is described below. You can read more about each part in this [article](https://designshack.net/articles/html/what-is-html-the-anatomy-of-an-html5-document/).

 ### The DOCTYPE

 ```html
 <!DOCTYPE html>
 ```
 The first line in an HTML file declares the type of document of the file.  In this case, the above says that this is an HTML5 file. The DOCTYPE tells the browser which type of HTML to expect, which in turn affects how the browser renders the page.

### The HTML tag:

 ```html
 <html>
  <!-- Everything Goes Here -->
</html>
 ```
 
 This is the root element of the HTML file. All your content should go inside the HTML tag.

 ### Head Element:
 ```html
	<head>
		<!-- Below is the title of the webpage -->
		<title>My Title</title>
		<!-- Below is the charset to use -->
		<meta charset="utf-8"/>
		<!-- This is the viewport, which is necessary for responsive design -->
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
	</head>
 ```

The content in the head section is information for the browser - things such as the title, meta data, and stylesheets to use for the webpage.


### Body Element:
 ```html
	<body>
		<!-- Page Content Goes Here -->
		<h1>Hello World</h1>
	</body>
 ```

 All of your HTML content should be put in the body tag.

