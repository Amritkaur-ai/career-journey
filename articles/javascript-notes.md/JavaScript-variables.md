# JavaScript Variables

## Introduction

JavaScript Variables are named containers which are used to store values. These values can be referenced and manipulated throughout a program. JavaScript is a dynamically typed language, meaning the data type of a variable is determined automatically at runtime, so you do not need to specify it when declaring a variable.

## Three ways of variable declaration

Variables can be declared in three different ways depending how the values should behave in the code.

- **var** - The variables declared as var are function-scoped and can also be redeclared. Modern application generally avoid using var because it can lead to unexpected behaviour when redeclared.
  ''' javascript
  var message = "hello";
  '''

- **let** - These are modern standard, block-scoped variables which cannot be redeclared but can be updated or reassigned later.
  ''' javascript
  let word1 = "Hello";
  let word2;
  word2 = "world";
  '''

- **const** - These are modern standard, block-scoped variables whose reference cannot be reassigned after declaration. A value must be assigned to these variables at the time of declaration.
  ''' javascript
  const word = "Hello";
  '''

## Rules for naming a variable

Each variable must be assigned a name. This name is know an **identifier**. Here are some rules which must be followed while assigning a name to variable in JavaScript:

- Identifiers must be **case-sensitive**.
- Name can only contain **letters, digits, underscore (\_) or dollar ($)**.
- Names can start with letters, underscore or dollar.
- Names cannot start with numbers.
- **Reserved Words** are not allowed as variable names.
- Variable names cannot contain spaces.
- Variable names should be meaningful and descriptive.

## Best Practices

- Use'const' by default.
- Use 'let' when a variable needs to change.
- Avoid using 'var' in modern JavaScript.
- Choose meaningful variable names.

## Summary

- Variables store data used by a program.
- JavaScript provides three ways to declare variables: 'var', 'let' and 'const'.
- 'let' and 'const' are preferred in modern JavaScript.
- Variable names should follow JavaScript naming rules.

**Date:** 6 July 2026
**Auther:** Amrit Kaur
**Status:** Published
