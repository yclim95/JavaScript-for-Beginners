#Session10 The Document Object

##Get the value of the input 

```html
<html>
	<head>
		<title>The Document Object</title>

		<script type="text/javascript">
			function processName()
			{
				var first;
				var last;

				first = document.getElementById("first").value;
				last = document.getElementById("last").value;

				alert(first + " " + last);

			}
		</script>
	</head>

	<body>
		First: <input type = "text" id = "first">
		<br />
		Last: <input type = "text" id = "last">
		<input type = "button" value = "Press Me!" onclick = "processName()"/>
	</body>
</html>
```


##Manipulating html elements's CSS style by ID 

```html
<html>
	<head>
		<title>The Document Object</title>

		<script type="text/javascript">
			function processName()
			{
				document.getElementById("para").style.backgroundColor = "#cc0000";
				document.getElementById("para").style.fontWeight = "bold";
			}
		</script>
	</head>

	<body>
		<p id = "para">This is YC's paragrapgh. lalasdsdjfaljdkjlakdfjaskjflad</p>
	</body>

</html>
```


##Inner HTML

Here we'll have a basic understanding of AJAX(Asynchronous JavaScript & XML). By using `innerHTML()`, it lets your able to dynamically change the content of the html elements without refreshing the page from the client browser. 

```html
<html>
	<head>
		<title>innerHTML</title>

		<script type="text/javascript">
			function changeContent()
			{
				document.getElementById("content").innerHTML = "<h3>See? The content has changed!</h3>"
			}
		</script>
	</head>

	<body>
		<div id = "content">
			<p>This paragraph will change when the document object's innerHTML property is accessed</p>
		</div>
		<input type = "button" value = "Press Me!" onclick = "changeContent()"/>
	</body>

</html>
```

## Exercise 
[Click here for exercise for this lesson]()