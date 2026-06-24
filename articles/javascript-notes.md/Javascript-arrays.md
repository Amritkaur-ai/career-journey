# JavaScript Arrays

## What is an array?

An array is a data structure used to store multiple values in a single variable. The values can be of the same or different data types.

## Creating an array

You can create an array in JavaScript by just assigning elements to it.
For example:
let fruits = ["apple", "banana", "mango"];
console.log(fruits);

## Accessing elements

To check for the specific element in the array, just write the array name along with its index in square brackets.
For example:
let fruits = ["apple", "banana", "mango"];
console.log(fruits[0]); //Prints apple
console.log(fruits[2]); //Prints mango

## Updating elements

We can also Update the elements in the array as done in below example
let fruits = ["apple", "mango", "banana"];
fruits[1] = "cherry";
console.log(fruits); //Output : apple, cherry, banana

## length

The length() property is used to print the length of an array
let fruits =["apple", "mango", "banana"];
console.log(fruits.length); //Output : 3

## Add element

We can add element in the start or end of the array. To add the element in the end, we use push() function and unshift() function is used to add the element at the index 0.
For example:
let fruits = ["apple", "mango", "banana"];
fruits.push("grapes");
fruits.unshift("cherry");
console.log(fruits); //Output : cherry, apple, mango, banana, grapes

## Remove Element

We can remove the element from the start or the end of the array. pop() is used to remove the element from the end and shift() is used to remove the element from the start.
For example:
let fruits = ["apple", "mango", "banana"];
fruits.pop();
console.log(fruits); //Output : apple, mango
fruits.shift();
console.log(fruits); //Output : mango

## Accessing element of an array

let fruits = ["apple", "mango", "banana"];
for( let i = 0; i < fruits.length; i++) {
console.log(fruits[i]);
}

or it can also be done using for of loop
let fruits = ["apple", "mango", "banana"]
for (let fruit of fruits) {
console.log(fruit);
}

## Checking for element in an array

let fruits =["apple", "mango", "banana"];
console.log(fruits.includes("banana")); // Output : true
console.log(fruits.inculdes("cherry")); // Output : false

## Summary

- Arrays store multiple values.
- Array indexing starts from 0.
- Use 'push()' and 'pop()' to add/remove elements from the end
- use 'unshift()' and 'shift()' to add/remove elements from the start
- Use 'length' to get the number of elements.
