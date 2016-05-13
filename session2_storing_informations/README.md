#Session2 Storing Information

## Variable 
In the previous lesson, we learned how to output to the browser and it seems alright to leave it like this. But, what will happen if we want to store the output for future purpose. 

Here comes the need of **variable**.

### 1. Variable Declaration 
`var` =  Variable 

```javascript
var userName; // Variable Declaration
```

### 2. Variable Initialization  

```javascript
userName = "YC Lim"; // Variable Initialization
```

### 3. Combined intialization/declaration
Commonly used to declare/intialize variable.  

```javascript
var userName = "YC Lim";
```

### 3. Output variable

```javascript
var userName; // Variable Declaration
userName = "YC Lim"; // Variable Initialization
document.write(userName); //Output the variable
```

### 4. Output numbers instead of Strings 

```javascript
var userAge = 21 // Combined initialization/declaration
document.write(userAge);
```

[Click here for the full source code for this part](https://github.com/yclim95/JavaScript-for-Beginners/blob/master/session2_storing_informations/variable.html)


## Operators & Operand
### 1. Operand

```javascript
var operandOne;
var operandTwo;

operandOne = 125; //Integer
operandTwo = 15.371; //Floating point Number

document.write(operandOne); //125
document.write("<br />");
document.write(operandTwo); //15.371
document.write("<br />");
```

### 2. Operators
#### A. Common Operation

```javascript
//Common operation 
document.write("Addition : " + (operandOne + operandTwo)); //140.371
document.write("<br />"); 
document.write("Substraction : " + (operandOne - operandTwo)); //109.629
document.write("<br />");
document.write("Multiplication : " + (operandOne * operandTwo));//1921.375
document.write("<br />");
document.write("Division : " + (operandOne / operandTwo));//8.13219699433999
document.write("<br />");
```

#### B. Additional Operation

`"%"` is called modulus is used to evaluate the remainder. 

```javascript
// Addition operation 
document.write("10 % 3 : " + (10 % 3)); //Remainder of 10/3
operandOne++; //Increment Operator (Add 1 to the var)
operandTwo--; //Decrement Operator (Subtract 1 from the var)

document.write("<br />");
document.write(operandOne);
document.write("<br />");
document.write(operandTwo);
```

#### B. PostFix && Prefix Operator

```javascript
var variable = 5;

variable++  //PostFix Increment Operator 
variable-- //PreFix Increment Operator 

PostFix //The rest of the mathematical expression is evaluated and then the increment/decrement take place

PreFix //The increment/decrement takes place and then the rest of the expression is evaluated

```

## Weird Things 
### 1. Cocatenation (+)
"+" in general is used as addition. But in programming, or at javaScript it has another function, which is **joining** a string of words to form a sentence. 

Oo What ..... Yeap .... "+" is addition in general. So, should'nt it give you an error instead. Well, just get used to it. 

```javascript
//Cocatenation (+)
var teamCity = "New York";
var teamName = "Yankees";

var fullTeamInfo = teamCity + " " + teamName;

document.write("<br />");
document.write(fullTeamInfo); //New York Yankees
```

[Click here for the full source code for this part](https://github.com/yclim95/JavaScript-for-Beginners/blob/master/session2_storing_informations/variable_operators.html)