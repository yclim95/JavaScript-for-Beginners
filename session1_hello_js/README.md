#Sesson1 Hello to JS

## Learn how to display text on browser

```javascript
document.write("Hello from javascript");
```

## Embedded HTML code 
You can give your text a format using embeded HTML code. Like :

```javascript
document.write("<strong>Hello from javascript</strong>");
```

You can [review the full code here](https://github.com/yclim95/JavaScript-for-Beginners/blob/master/session1_hello_js/first_javascript.html) 

## Where to place the Javascript code `<script>` tag
There is 3 ways placing it : 

1. Place between the `<body>` tag

```html
<body>
	<script type="text/javascript">
		//Output to the browser 
		document.write("Hello from javascript<br/>");
	</script>
</body>
```

2. Place between the `<head>` tag

```html
<head>
	<title>First Javascript</title>
	<script type="text/javascript">
		//Output to the browser 
		document.write("Hello from javascript<br/>");
	</script>
</head>
```
3. Use an external .js file and place in the `<head>`tag (attached. javascript)

```html
	<body>
		<script language="javascript" type="text/javascript" src="attached.js"></script>
	</body>
```

Normally, it is recommended to place Javascript code `<script>` tag between `<body>` tag. Reason is because, the statement inside `<body>` tag is only executed. 

That's why we normally place `function` inside the `<head>` tag & call back the function in `<body>` tag to execute the command in the function. 


[Click Here to Lab Exercise 1](https://github.com/yclim95/JavaScript-for-Beginners/tree/master/session1_hello_js/lab_exercise_1)