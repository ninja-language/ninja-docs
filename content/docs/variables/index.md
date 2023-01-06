---
title: "Variables"
date: 2023-01-06T22:09:29Z
draft: false
weight: 1
---


# Introduction  

Here is a summary of the different types of variables and how to declare them in Ninja programming language:

## Numbers  

Numbers in Ninja can be either integers (whole numbers) or floats (numbers with a decimal point). 
To declare a number, use the var keyword followed by the name of the variable you want to create, and then assign it a value. 
For example:  


```
var a = 1;        // declares an integer
var b = 2.0;      // declares a float
```

## String  

A string is a sequence of characters (letters, numbers, symbols, etc.) surrounded by quotation marks. 
To declare a string, use the `var` keyword followed by the name of the variable you want to create, and then assign it a 
string value. 
For example:

```
var name = "John";  // declares a string
```  

## Arrays  

An array is a data structure that stores a collection of values. To declare an array, use the `var` keyword 
followed by the name of the variable you want to create, and then assign it an array of values surrounded by square brackets. 
For example:  

```
var numbers = [1, 2, 3];  // declares an array of numbers
var mixed = [1, "two", 3.0];  // declares an array with mixed types
```  

## Hashes  

A hash is a data structure that stores a collection of key-value pairs. To declare a hash, use the `var` keyword 
followed by the name of the variable you want to create, and then assign it a hash literal (a collection of key-value 
pairs surrounded by curly braces). 
For example:  

```
var person = {name: "John", age: 30};  // declares a hash
```  

## Functions  

Functions: A function is a block of code that can be called (executed) multiple times. To declare a function, use the `var` 
keyword followed by the name of the variable you want to create, and then assign it a function definition 
(a block of code surrounded by the `function` keyword and curly braces). 
For example:  

```  
var add = function (a, b) {
  return a + b;
};  // declares a function
```  

## Booleans  

A boolean is a data type that can have only two values: true or false. To declare a boolean, use the var 
keyword followed by the name of the variable you want to create, and then assign it a boolean value. 
For example:  

```  
var isTrue = true;  // declares a boolean
var isFalse = false;  // declares a boolean
```  