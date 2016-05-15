#Lab Exercise 10

1. Load Chapter 10 Lab Starter.html in to your text editor and examine the code. Notice that there is an onblur event associated with each input field. This event will fire the associated function when the text box loses focus. Notice also the empty span to the right of each input field in the table.

2. We’re going to create a form that provides the user with immediate feedback if they leave a required field blank. For the purpose of this exercise all fields are required.

3. Place an `alert` box that outputs `“In validFirst()”` in the validFirst function. Load the page in to a browser and test when the function fires by changing the value in the first name text box.

4. Comment out the `alert` box.

5. Code the `validFirst` function so that when the user changes the value in the first name text box the content in the checkbox is validated to insure the textbox hasn’t been left blank. To do this, you must make sure that the text box value is both not equal to null or to an empty string.

6. If the text box is either null or equal to an empty string, than use the innerHTML property to place the words “Required Field” in the span to the right of the text box.

7. Additionally if the text box is either null or equal to an empty string , change the `style. backgroundColor` property of the text box to **red**.

8. Test and debug as necessary to insure that that the appropriate message is displayed and the text box turns red when left blank.

9. Add some text to the text box in the browser and notice that the span does not clear, nor does the background color return to white.

10. Add an else condition to your if statement that clears the text in the span and resets the `style.backgroundColor` property of the textbox to **white**.

11. Test again. When working properly apply the same logic to get the three other text boxes to behave identically.

12. Add an additional behavior to each text box—Make sure the length of the string in the text box is **at least 2** letters. If it’s less than two letters output the message in the span “Response too short”

**Output**

![Output]()


**Sample Code**

1. [Click here for full sample code]()