# JavaScript Data Types

## Introduction

Data Type defines what kind of value can be store in a variable and what actions can be performed on it. JavaScript is a dynamically typed language which means data type of a variable can change automatically at runtime.

## typeof operator

We can use typeof operator to check the data type of a variable. For example,

''' javascript
typeof 42; // Output : "number"
'''

## Data Types

Data Types in JavaScript can be categorized as:

- Primitive Data Types
- Non-Primitive Data Types

## Primitive Data Types

Primitive Data Types are simple, immutable values which are stored directly in the memory. These can be further divided into seven types:-

- **number** - The number type represents integers and floating-point values. It also includes the special numeric values Infinity, -Infinity, and Nan(Not-a-Number).
  Examples:
  ''' javascript
  let s1 = 2;
  console.log(s1); // Output: 2

let s2 = Infinity;
console.log(s2); // Output: Infinity

let s3 = 'Hello' / 2;
console.log(s3); // Output: Nan
'''

- **string** - consists of combination of letters or words enclosed in single quotes(''), double quotes(""), or backticks(``).
Examples:
''' javascript
 let s1 = "Hello World";
 console.log(s1); // Output: Hello World
 let s2 = 'Hello India';
 console.log(s2); // Output: Hello India
 let s3 = `Wow ${s1}';
  console.log(s3); // Output: Wow Hello World
  '''

- **boolean** - Represents a logical entity which can have only 2 values: true or false
  Example:
  ''' javascript
  let s1 = true;
  console.log(s1); //Output: true
  console.log(typeof(s1)); //Output: boolean
  '''

- **null** - represents an intentional, explicit absence of any object values or reference.
  Example:
  ''' javascript
  let age = null;
  console.log(age); // Output: null
  console.log(typeof age); //Output: "object"
  '''
  This is a historical bug in JavaScript that has been kept for backward compatability.

- **Undefined** - it is assigned automatically to a variable which is declared but no value is assigned to it.
  Example:
  ''' javascript
  let s;
  console.log(s); // Output: undefined
  console.log(typeof s); // Output: "undefined"
  '''

- **Symbol** - represents a unique and unchangeable variable used as a secure key for object properties.
  Example:
  ''' javascript
  let s1 = Symbol("Hello");
  let s2 = Symbol("Hello");
  console.log( s1 == s2 ); //Output: false
  '''

- **BigInt** - represents whole Integer numbers larger than safe standard limit. These are created by appending n to integers.
  Example:
  ''' javascript
  let s = 9999999999999999n;
  console.log(s); //Output: 9999999999999999
  console.log(typeof(s)); //Output: bigint
  '''

## Non-Primitive Data Types

Non-Primitive Data Types are dervived from Primitive data types. These are mutable types which can hold properties and methods. These are stored by reference in the memory heap. These are also known as Dervied Data Types or Reference Data Types. Object is a Non-Primitive Data Type.

- **object** - Object is used to store complex collection structures and custom data entities as key-value pairs. It includes Arrays and functions as well.
  Example:
  ''' javascript
  let s1 = {
  country : "India";
  state : "Punjab";
  console.log(s1.country); // Output: India
  }
  '''

## Summary

- Data Types represent the type of value stored in a Variable.
- JavaScript is a dynamically typed language.
- 'typeof' operator is used to determine the data type of a value or a variable.
- Categorized as Primitive and Non-Primitive Data Types
- JavaScript has seven Primitive Data Types:
  - number
  - string
  - boolean
  - null
  - undefined
  - symbol
  - BigInt
- Objects are non-primitive data types used to store collections of data.

**Date:** 7 July 2026
**Auther:** Amrit Kaur
**Status:** Published
