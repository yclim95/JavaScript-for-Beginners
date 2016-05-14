#Lab Exercise 6

##Part 1:
1. Download and load the file labStarter.html in to your text editor.

2. Place a `<script>` element in the document head with the appropriate attributes and values so you can add Javascript code.

3. In the script element you just created, write the signature of the following functions:


```
english()
spanish()
hebrew()
french()
```

The function will be called when the corresponding button is clicked due to the onclick attribute in each `<input>` element.

4. Code each function so that it outputs an appropriate greeting language when the button is clicked using an `alert()` box.

```
English = Hello! How are you?
Spanish = Hola. Como estas?
Hebrew = Shalom!
French= Bon Jour!
```

Save your completed file. Test and insure that it works correctly.


##Part 2:

5. Create a new document using the HTML basic document structure demonstrated earlier by the instructor.

6. Create four buttons labeled “Add”, “Subtract”, “Multiply” and “Divide”. Use onclick attributes to call an appropriate function named `add()`, `subtract()`, `multiply()` or `divide()` when the corresponding button is clicked.

7. In the document head create <script> tags with the appropriate attributes and values so that you may place Javascript.

8. Add the add(), subtract(), multiply() and divide() functions to the script element in the document head.

9. When you call the functions from the onclick event, pass them any two integers. Each function should output the resulting math of adding, subtracting, multiplying or dividing the integers.

10. Save and test. Once your code is working, optimize your code so the same thing can be accomplished with a single function in the head called `mathProb()`. This function should be passed three parameters—the two integers and a symbol-- +, -, * or / indicating the mathematical function to be performed.



**Sample Code**

1. [Click here for full sample code Part 1](lab_exercise6_part1.html)
2. [Click here for full sample code Part 2](https://github.com/yclim95/JavaScript-for-Beginners/blob/master/session6_functions/lab_exercise6/lab_exercise6_part2.html)