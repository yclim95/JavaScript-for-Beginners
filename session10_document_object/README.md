#Session10 The Document Object

##Get the value of the input 

```html
First: <input type = "text" id = "first">
<br />
Last: <input type = "text" id = "last">
<input type = "button" value = "Press Me!" onclick = "processName()"/>
```

```javascript
function processName()
{
	var first;
	var last;

	first = document.getElementById("first").value;
	last = document.getElementById("last").value;

	alert(first + " " + last);
}
```

##Manipulating html elements's CSS style by ID 

```html
<p id = "para">This is YC's paragrapgh. lalasdsdjfaljdkjlakdfjaskjflad</p>
```

```javascript
function processName()
{

	document.getElementById("para").style.backgroundColor = "#cc0000";
	document.getElementById("para").style.fontWeight = "bold";

}
```

##Inner HTML

Here we'll have a basic understanding of AJAX(Asynchronous JavaScript & XML). By using `innerHTML()`, it lets your able to dynamically change the content of the html elements without refreshing the page from the client browser. 

```html
<div id = "content">
	<p>This paragraph will change when the document object's innerHTML property is accessed</p>
</div>
<input type = "button" value = "Press Me!" onclick = "changeContent()"/>
```

```javascript
function changeContent()
{
	document.getElementById("content").innerHTML = "<h3>See? The content has changed!</h3>"
}
```