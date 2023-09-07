Now this is where css becomes some less haptic because now we can reuse css in a whole lot of places. we can accomplish by creating a class selector in css and adding the styles to it.

```css 

/* simply put a dot in front to declare it a class*/

.hello-css {
	margin: auto;
	background-color: brown;
}
```

now in out html element we can simply add the `class` attribute and inside the name of the class.

```html 
<element class="hello-css"> content </element>
```

