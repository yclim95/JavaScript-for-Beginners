#Session9 Obtaining & Manipulating User Information

## 1. Navigator Object 

```javascript
document.write("Code Name of the browser: " + navigator.appCodeName);
document.write("<br />");
document.write("Name of the browser: " + navigator.appName);
document.write("<br />");
document.write("Version of the browser: " + navigator.appVersion);
document.write("<br />");
```

## 2. Window Object 

```javascript
//Window Object
document.write("Document: " + window.document);
document.write("<br />");
document.write("Width: " + window.innerWidth);
document.write("<br />");
document.write("Height: " + window.innerHeight);
document.write("<br />");
```

## 3. Location Object 
`window.location` not just get and set the location but also able to redirect u to another page. 

```javascript
//Loaction Object
document.write("Location " + window.location);
//window.location = "http://www.cnn.com";

document.write("<br />");
document.write("Location Protocol File " + window.location.protocol);
```

## 4. Screen Object 

```javascript
//Screen Object 
document.write("<br />Screen Height: " + screen.height);
document.write("<br />Screen Color Depth: " + screen.colorDepth);
```

## Resources
1. [Window Objects documentation](http://www.w3schools.com/jsref/obj_window.asp)
2. [Navigator Objects documentation](http://www.w3schools.com/jsref/prop_nav_cookieenabled.asp)
2. [Screen Objects documentation](http://www.w3schools.com/jsref/obj_screen.asp)

## Exercise 
[Click here for exercise for this lesson]()