### Image tag
used to add images.
`<img src="link" alt="text" ></img>`

	1. alt
is used for adding text incase image does not load.

here is an example of how images is added.
```html
<img src="pic_trulli.jpg" alt="Trulli">
```

![[Pasted image 20231023145619.png]]

### Favicon

it is defined in the head to add logo of the website to the webpage.
`<link rel="icon" type="image/x-icon" href="/images/favicon.ico">`

	1. type
specifies logo

	2. href
provides link to the image

remember its an ICO file.

### Emojis

yes we can also add emojis but due to the UTF-8 encoding we need to add it with some specific texts.
here is an example:
```html
<p>&#128512;</p>
```

![[Pasted image 20231023150016.png]]

here is the list to all the emojis and their specific format.
https://www.w3schools.com/charsets/ref_emoji_smileys.asp

### Audio

```html
<audio controls>
  <source src="file1.ogg" type="audio/ogg">
  <source src="file2.mp3" type="audio/mpeg">
Your browser does not support the audio element. (message to the browser)
</audio>
```

simple as that.

### Vedio

```html
<video width="320" height="240" controls>  
  <source src="file1.mp4" type="video/mp4">  
  <source src="file2.ogg" type="video/ogg">  
  Your browser does not support the video tag.  
</video>
```


