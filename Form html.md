use do develop form with the use of html


### Action parameter 

action is use to signify where the form content will be submitted 

here is an example 
```html 
<html>
	<body>
		<form action='/submit-url'></form>
	</body>
</html>
```

### Input tag 

input tags are self closing tags and do not require any closing tag.

input tag allows us to take different types of input from the user. You can use the type attribute to make chose the type of input. It can be a text, button or a control to chose the file from the users system.

here is an example 
```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text">
		</form>
	</body>
</html>
```

in order to organize data properly we use name attribute to assign the input field with some name to recognize.

here is an example

```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName">
		</form>
	</body>
</html>
```

we can use placeholder attribute to hint the user what to fill in the input

```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user">
		</form>
	</body>
</html>
```

