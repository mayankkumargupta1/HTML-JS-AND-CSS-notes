use do develop form with the use of html


### Action parameter 

`action` is use to signify where the form content will be submitted 

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

input tag allows us to take different types of input from the user. You can use the `type` attribute to make chose the type of input. It can be a text, button or a control to choose the file from the users system.

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

in order to organize data properly we use `name` attribute to assign the input field with some name to recognize.

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

we can use `placeholder` attribute to hint the user what to fill in the input

```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user">
		</form>
	</body>
</html>
```

to make an input field mandatory and to make the user submit the form only when all the input fields are filled. We use another attribute called `required`

lets add the attribute 
```html
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" required>
		</form>
	</body>
</html>
```

### Button Tag 

to submit the form we use button, and to add these buttons we use button tag 

```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" required>
			<button>click me</button>
		</form>
	</body>
</html>
```

normally if we don't specify any attribute to the button. It will submit the form to the specified path.

but still adding `type` attribute with value submit to make it clear that it is a submit button 

```html 
<html>
	<body>
		<form action='/submit-url'>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" required>
			<button type="submit">click me</button>
		</form>
	</body>
</html>
```

####  Radio button 

we can add radio buttons when we want to only get one type of answer from the user.
you just need to change the `type` attribute to radio.
lets add one to our code 

```html
<html>
	<body>
		<form action='/submit-url'>
			<input type="radio">Radio
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" required>
			<button type="submit">click me</button>
		</form>
	</body>
</html>
```

### Label tag 

`label` tag helps in labelling the input fields. so if the label is clicked the radio button is also clicked. 

here is an example of such.
```html 
<html>
	<body>
		<form action='/submit-url'>
			<label><input type="radio">Radio</label>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" required>
			<button type="submit">click me</button>
		</form>
	</body>
</html>
```

### ID attribute

`id` attribute helps in identifying a specific element in an html document. We do require these when working with javascript and css to modify the element or to get use of it.

lets add `id` attribute to all the input fields
```html
<html>
	<body>
		<form action='/submit-url'>
			<label><input type="radio" id="input1">Radio</label>
			<input type="text" name="someMeaningfullName" placeholder="info you want from user" id="input2" required>
			<button type="submit" id="button">click me</button>
		</form>
	</body>
</html>
```

this is what we have created so far 
![[Pasted image 20230906125703.png]]


### Handling multiple radio button 

in some cases we want only one radio button to be selected and not both of them
in this case we will use `name` and `id` attribute to accomplish this.

here is an example:
```html 
<html>
	<body>
		<form action="/submit-url">
			<label><input type="radio" id="opt1" name="opt1-opt2">option1</label>
			<label><input type="radio" id="opt2" name="opt1-opt2">option 2</label>
		</form>
	</body>
</html>
```

![[Recording 2023-09-06 190400.mp4]]

