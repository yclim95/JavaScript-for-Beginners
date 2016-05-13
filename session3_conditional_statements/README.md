#Session3 Conditional Statement

## Conditional Operator 

```
/*
Comaprison Operators

<b>==</b>  Equivalence 
<b>===</b> Equaivalance in value & type
	1 == "1" true
	1 === "1" false
<b>></b> Greater than 
<b><</b> Less than 
>= Greater than or =
<= Less then or  =
!= Not Equal to 

&& AND 
|| OR


*/
```

## Conditional IF Statement 
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

`&&` (AND) will return true if only if the 2 condition is TRUE else if will return FALSE. 

`||` (OR) will return FALSE if only if the 2 condition have not met and will return TRUE otherwise.