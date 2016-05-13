#Session4 Dialog Boxes
Here we are introducing 3 different dialog boxes which is used to interact with the users. 

## 1. Alert box

```javascript
// 1. Alert box
//alert("Have a nice day");

var message = "Have a nice day";
alert(message);
```

## 2. Confirm box

```javascript
// 2. Confirm box 
var confirmation = confirm("Are you sure you want to exit?"); //return true or false

if (confirmation == true){
	document.write("Exiting application");
}else{
	document.write("Cancel exit");
}

document.write("<br />");
```

The value return from variable `confirmation` is either true or false.

## 3. Prompt box

```javascript
//3. Prompt dialog box
var age = prompt("What is your age?", "");
document.write("You are " + age + " years old");

if (age > 18){
	document.write("<br />You are older than 18 years old");
}
```

`prompt` is used to get answer from the user. 


## Exercise 
[Click here for exercise for this lesson](https://github.com/yclim95/JavaScript-for-Beginners/tree/master/session4_dialog_boxes/lab_exercise4)