#Session8 String Object

## 1. length()

```javascript
//length
var pharase = "If you are strong enough there are no precedents.";

document.write("Length: " + pharase.length);
document.write("<br />");
``` 

## 2. charAt()

```javascript
//charAt() --> Character @ a specified position in the string 

for(var i=0 ; i < pharase.length; i++){
	document.write(i + ": " + pharase.charAt(i));
	document.write(" | " + pharase.charCodeAt(i));//uniCode
	document.write("<br />");
}
``` 

## 3. indexOf()

```javascript
//indexOf()
document.write("Index of s: " + pharase.indexOf(
	's'));

document.write("<br />");
```

## 4. replace()
Does not manipulate the memory content value directly. 

```javascript
//Replace() --> Does note change the memory

pharase = pharase.replace("strong","attractive");
document.write(pharase);

document.write("<br />");
```

## 5. split()

```javascript
//split() => From string to Array
var names = "Mark,Bob,Tom,Brett,Mary,Lester,Charles";

var moreNames = names.split(',');
document.write("<br />");


for (var i = 0; i < moreNames.length; i++){
	document.write(moreNames[i]);
	document.write("<br />");
}
```

## References 
1. [Object String Properties & Methods](http://www.w3schools.com/jsref/jsref_obj_string.asp)

## Exercise 
[Click here for exercise for this lesson]()