# prompt() Function

## Introduction to prompt() function

The 'prompt()' function in JavaScript is used to take the input from the user. It pauses the execution of the script until the user enters a value and submits the response or close the window.

## Syntax

'''JavaScript
let name = prompt(message, defaultText);
'''

Here,

- 'name' is a variable in which the user's input is stored.
- 'message' is an optinal string which will display the message or question to the user.
- 'defaultText' is an optional value that sets the default text for input field.

## Return Value

- **String :** Returned when the user enter some text and click **OK**.
- **Empty String('""') :** Returned when user clicks **OK** without entering any text.
- **'null' :** Returned when the user clicks **Cancel** or closes prompt dialog.

## Example

''' JavaScript
let name = prompt("enter your name", "Guest");
console.log(name);
'''

## Summary

- 'prompt()' function is used to take input from the user
- it pauses the execution of the script until the user responds.
- The return type can be string, empty string or null.

**Date:** 25 June 2026
**Auther:** Amrit Kaur
**Status:** Learning JavaScript 'prompt()' function
