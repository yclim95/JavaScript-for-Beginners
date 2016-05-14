#Session7 Arrays

##1. Declaring Arrays
Array is an object that has its own properties and methods.

###1. Standard Arrays

```javascript
//Standard Array 
var firstNames = new Array(); //Instantiation of an Array()Object
firstNames[0] = "Mark";
firstNames[1] = "Collen";
firstNames[2] = "Brett";
firstNames[3] = "Joan";
firstNames[4] = "Rick";
``` 

###2. Condenced Method 

```javascript
var animals = new Array("dog", "cat", "mouse", "hampster", "toad");
``` 

###3. Literal Array

```javascript
//Literal Array
var companies = ["Apple","Google","Cnet","Udemy","GE"];
``` 

##2. Displaying Array 
###1. Basic

```javascript
alert(firstNames[3]);
alert(animals[0]);
alert(companies[2]);
```

###2. Use Loop to access and display all elements 

```javascript
//To Access & display all the element 
for (var i = 0; i < firstNames.length; i++){
	document.write(firstNames[i] + "<br />");
}
```

##3. Manipulating Array 
###1. For in loop
You would not need to know what is the condition you need to meet to exit the loop. It will loop until there are no elements left. 

```javascript
var grades = [85,92,70,63,55,92,88,71,91,91];

for (x in grades)
{
	document.write("Iteration: " + x + "<br />");
	document.write("Grade: " + grades[x] + "<br />");
}
```

###2. Push() 


###3. Pop()



##Resources 
1. [JavaScript Array Reference](http://www.w3schools.com/jsref/jsref_obj_array.asp)

## Exercise 
[Click here for exercise for this lesson](https://github.com/yclim95/JavaScript-for-Beginners/tree/master/session7_arrays/lab_exercise7)