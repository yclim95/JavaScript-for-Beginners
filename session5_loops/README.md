#Session5 Loops
There are 3 types of loops you can use to iterate to ease us for speeeding up the work. 

## 1. While loop
If the conditional met is false, it would not execute and will exit the loop.

```javascript
// 1. while Loop
var x = 0;

//Loop that count to 100
while (x <= 100){ //If false fail to iterate the loop
	document.write(x + "<br />");
	x++;
}
```

## 2. Do-While Loop
`Do-while` loop is different with `while` loop, whereby the the loop will execute the first time(at least ONCE), BUT the following time, the condition will be check. If is met, the loop will be executed, else it will exit the loop.

```javascript
// 2. Do-While Loop
var y  = 0;
do{
	document.write(y + "<br />");
	y++;
}while(y <= 100); //Exit loop while y is more or equal to 100
```

## 3. For Loop

```javascript
// For loop
for (var i=0; i <= 100; i++){
	document.write(i + "<br />");
}
```

In `for` loop, there are 3 important parts. `var i=0;` is the variable initialization. `i <= 100;` is conditional iteration & `i++` is the counter.


## Use Loop to prompt input 

```javascript
var ui = "";
while (ui != "xxx"){
	ui = prompt("Enter a name of one your favourite bands. Enter xxx to stop! ");
	if (ui != "xxx"){
		document.write(ui + "<br />");
	}
}
```

## Weird Part 

```javascript
var theNumber = prompt("Enter a Number"); //Treated as a string
document.write(theNumber + 1); //Concatenation 
```

```
Let's say the user key in 7 for the input. 
What do you think of this answer be ? 
8 ? or ? 
```

Hmm... what do you think ? BANG ~~ The answer is NOT. The answer is `71`. WHAT !!! 

Well, when dialog box is used to get an input from the user is treated as a string. So when you `document.write(theNumber + 1)`. It automatically treats `"+"` as concatenation. 

**Here is the solution**

```javascript
//To solve this 
var theNumber = parseFloat(prompt("Enter a Number"));
document.write(theNumber + 1); 
```

`parseFloat()` will retain the position of the number. 



## Exercise 
[Click here for exercise for this lesson]()