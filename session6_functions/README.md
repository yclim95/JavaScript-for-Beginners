#Session6 Functions

This time we import an external javascript(.js) file. 

**function.html**
```html
<html>
	<head>
		<title>Functions</title>
		<script type="text/javascript" src="function.js"></script>
	</head>
	<body>
		<script type="text/javascript">
			//Function calls
			displayGreeting();
			document.write("<br />");
			displayPlayerScore();
		</script>
	</body>
</html>
```

**function.js**
```javascript
//Function Definitions 

function displayGreeting()
{
	document.write("Hey there, dude!");
}

function displayPlayerScore () {
	var playerScore = 1000;
	document.write("<br />Player score: " + playerScore);
}
```

Notice here, the **function calls** in between the script tag inside the html file while the **function definitions** put inside the javascript(.js) file. 


## More dynamic 

**function.html**
```html
<html>
	<head>
		<title>Functions</title>
		<script type="text/javascript" src="function.js"></script>
	</head>
	<body>
		<script type="text/javascript">
			//Function calls
			displayGreeting();
			document.write("<br />");
			displayPlayerScore(125000);
		</script>
	</body>
</html>
```

**function.js**
```javascript
//Function Definitions 

function displayGreeting()
{
	document.write("Hey there, dude!");
}

function displayPlayerScore (theScore) {
	//var playerScore = 1000;
	document.write("<br />Player score: " + theScore);
}
```

## Return keyword

**function.html**
```html
<html>
	<head>
		<title>Functions</title>
		<script type="text/javascript" src="function.js"></script>
	</head>
	<body>
		<script type="text/javascript">
			//Function calls
			var sum = addTheseNumbers(5,4)
			document.write("<br />" + sum);
		</script>
	</body>
</html>
```

**function.js**
```javascript
//Function Definitions 
function addTheseNumbers(x,y)
{
	//document.write("<br />" + (x+y));
	return(x+y);
}
```

### Alternative ways (Return)


**function.html**
```html
<html>
	<head>
		<title>Functions</title>
		<script type="text/javascript" src="function.js"></script>
	</head>
	<body>
		<script type="text/javascript">
			//Function calls
			//var sum = addTheseNumbers(5,4)
			document.write("<br />" + addTheseNumbers(5,4));
		</script>
	</body>
</html>
```

**function.js**
```javascript
//Function Definitions 
function addTheseNumbers(x,y)
{
	//document.write("<br />" + (x+y));
	return(x+y);
}
```

## Calling Functions from event

### 1. onClick 

```html
<html>
	<head>
		<title>Events</title>
		<script type="text/javascript">
			function onButtonClick()
			{
				alert("You have successfully pressed the button!");
			}

		</script>
	</head>

	<body>
		<input type="button" value="Press Me" onclick="onButtonClick()"/> 
	</body>

</html>
```

### 2. onLoad function

`onLoad` = when the page is succesfully loaded. 

```html
<html>
	<head>
		<title>Events</title>
		<script type="text/javascript">

			function whenPageLoads()
			{
				alert("Welcome to my page");
			}
		</script>
	</head>

	<body onLoad="whenPageLoads()">

	</body>

</html>
```

### 2. onmouseover function


```html
<html>
	<head>
		<title>Events</title>
		<script type="text/javascript">
			function onButtonClick()
			{
				alert("You have successfully pressed the button!");
			}
		</script>
	</head>

	<body>
		<input type="button" value="Press Me" onmouseover="onButtonClick()"/> 
	</body>

</html>
```


## Exercise 
[Click here for exercise for this lesson](https://github.com/yclim95/JavaScript-for-Beginners/tree/master/session6_functions/lab_exercise6)