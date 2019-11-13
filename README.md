# JavaScript practice
## Learning JS in SoloLearn

> x = y will assign the value of y to x

> a variable declared without a value will have the value **undefined**

> JavaScript `strings` are used for storing and manipulating text

### Backslash escape
![alt text](https://miro.medium.com/max/1518/0*EROX6jTOAMi7ITwn.jpg)

The **Boolean** value of 0(zero), `null`, `undefined`, `empty string` is **false**. Everything with a real value is **true**.

### Comparison operators
![alt text](https://apprize.info/javascript/20lessons/20lessons.files/image041.jpg)

### Logical operators
![alt text](https://i.pinimg.com/originals/44/67/a1/4467a199ba567016121beafdb4c5c5e4.png)

### Ternary operator
``` javascript
variable = (condition) ? (value1):(value2)

var isAdult = (age < 18) ? "Too young": "Old enough";
```
### Switch statement
```javascript
switch (//Some expression) {
  case 'option1':
    // do something;
    break;
  case 'option2':
    // do something else;
    break;
  default:
    // do yet another thing;
    break;
 }
 ```
 ```javascript
 switch (userInput) {
 case 'Hi!':
 alert('Hello!');
 break;
 case 'Bye!':
 alert('Goodbye!');
 break;
 default:
 alert('I am good, thanks.');
 break;
 }
 ```
 The **break** keyword breaks out of the `switch` block; should put in each `case` statement.
 The **default** keyword specifies the code to run if there is no `case` match.

### For loop
```javascript
for ( var i = 0; i <= 5; i++) {
  console.log(i);
}
```
**Statement1** is executed before the loop; sets a variable before the loop starts (var i = 0).

**Statement2** defines the condition for running the loop (i must be less or equal to 5).

**Statement3** increases a value (i++) each time after the loop has been executed.

### While loop

The **while** loop repeats through a block of code, as long as a specified condition is **true**. Make sure that the condition in a while loop eventually becomes **false**. 

#### Break and continue
The **break** statement jumps out of a loop and continues executing the code after the loop.

The **continue** statement breaks only one iteration in the loop and continues with the next iteration.

### JavaScript Keywords and Reserved Words 
![alt text](https://i.pinimg.com/originals/2e/dc/5c/2edc5c169bd1117e93bb327a2b318f60.jpg)

### Functions

If a function is called with missing arguments (fewer than declared), the missing values are set to **undefined**, which indicates that a variable has not been assigned a value.

A function can have an optional **return** statement. It is used to return a value from the function. This statement is useful when making caluculations that require a result.

## The Alert Box

JavaScript offers three types of popup boxes - **alert**, **prompt**, and **confirm** boxes.

An `alert` box is used when you want to ensure that information gets through to the user. When an alert box pops up, the user must click OK to proceed.

The **alert** function takes a single parameter, which is the text displayed in the popup box.
```javascript
alert('Do you really want to close this page?')
```
To display **line breaks** within a popup box, use a *backslash followed by the character n*.
```javascript
alert('Hello!\nHow are you?')
```
## The Prompt Box

A `prompt` box is often used to have the user input a value before entering a page. When a prompt box pops up, the user will have to click either *OK* or *Cancel* to proceed after entering the input value.

If the user clicks OK, the box **returns the input value**. If the user clicks Cancel, the box returns **null**.

The `prompt() method` takes **two parameters**. 
- The first is the label, which you want to display in the text box.
- The second is a default string to display in the text box (optional).

```javascript
var userName = prompt('Please enter your name');
alert(userName);
```


| Code | | Output |
| --- | --- | --- |
| \' | | single quote |
