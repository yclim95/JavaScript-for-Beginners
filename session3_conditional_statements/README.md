#Session3 Conditional Statement

## 1. Conditional Operator 

```javascript
/*
Comaprison Operators

==  Equivalence 
=== Equaivalance in value & type
	1 == "1" true
	1 === "1" false
> Greater than 
< Less than 
>= Greater than or =
<= Less then or  =
!= Not Equal to 

&& AND 
|| OR


*/
```

## 2. Conditional IF Statement 
`if` is used to compare something. It pretty come in handy especially when you want to evaluate something & it is easy to learn. 

```javascript
var age = 19; //Combined declaration & initialization

if (age >= 18 ){ //Conditional 
	document.write("You can vote<br/>");
}
```

```javascript
var name = "YC";

if (name == "YC"){
	document.write("You are the course instructor");
}
```

Al'right it looks pretty cool. But, what happen if you would like to compare more than 1 things in a statement. You could use `"&&"`(AND) & `"||"`(OR) symbol. 


```javascript
var age = 19; //Combined declaration & initialization
var citizen = true; //Boolean Variable

if (age >= 18 && citizen == true){ //Conditional 
	document.write("You can vote<br/>");
}
```

`&&` (AND) will return true if only if the 2 condition is **TRUE** else if will return **FALSE**. 

`||` (OR) will return **FALSE** if only if the 2 condition have not met and will return **TRUE** otherwise.


## Conditional If-Else Statement 

```javascript
var playerScore = 25000;
var highScore = 10000;

if (playerScore > highScore){
	highScore = playerScore;
	document.write("You attained the high score!"); //Output
}else{
	document.write("You did not attain the high score.");
}
```

## 3. Conditional Else-If statement

Hmm... we already learn how to use if-else statement and it seems al'right. But what if we would want to compare more than 2 ? Then, we have to use the **else-if** statement. 

```javascript
var numericalGrade = 95
var letterGrade;

if (numericalGrade >= 90){
	letterGrade = "A"; //if this is true, execute this
}else if (numericalGrade >= 80){
	letterGrade = "B"; //if this is true, execute this
}else if (numericalGrade >= 70){
	letterGrade = "C"; //if this is true, execute this
}else if (numericalGrade >= 60){
	letterGrade = "D"; //if this is true, execute this
}else{
	letterGrade = "F"; //if this is true, execute this
}

document.write("<br />Your grade is " + letterGrade);
```

## 4. Switch statement 

There is an alternative for else-if statement which is more neater and more readable comapre to else-if statment. 


```javascript
			var letterGrade = "A";

			switch (letterGrade){
				case "A":
				case "a":
					document.write("A is an execellent grade!");
					break;

				case "B":
				case "b":
					document.write("B is a good grade!");
					break;

				case "C":
				case "b":
					document.write("C is an average grade!");
					break;

				case "D":
				case "d":
					document.write("D is a low passing grade!");
					break;

				case "F":
				case "f":
					document.write("F is a failure. You must repeat this course");
					break;

				default:
					document.write("Grade is not recognized!");
```

The keyword `break` is use after the case statement as you can see except for the default statement. If letterGrade is equal to "A" and it go inside the switch and look for the case that matches that. If the 1st case does not match if will break of and go to the following one until it reaches the right place, else if none of them met the requirement, then the default statement will be executed.