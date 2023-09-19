- [[text-align css]]
- [[grouping style]]
- [[additional meta tags for better webpage]]
- [[Background color css]]
- [[Div tag]]
- [[Width css]]
- [[comment in css]]
- [[Margin in css ]]
- [[CLASSES in css]]
- [[Background Image in css]]
- [[Display Css]]
- [[Join similar class]]
- [[Padding css]]
- [[Font]]
- [[Use of Hr tag]]
- [[Border css]]
- [[Styling links in css]]
- 


to add `css` to you web page and to make it look good. You first need to add 
`style` tag within the head tag.

here is an example
```html 
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Sample Web Page</title>
		<meta charset="UTF-8">
		<!-- here you can add your css -->
		<style></style>
	</head>
</html>
```

#### or 

you can also create a separate .css file to add css to your web page.
now add the css file to you web page by creating a `link` tag nested in your head tag.

```html 
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Sample Web Page</title>
		<meta charset="UTF-8">
		<!-- now your css file is conected -->
		<link rel="stylesheet" href="styles.css">
	</head>
</html>
```