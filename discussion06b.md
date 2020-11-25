[Home](https://pmargellos.github.io/reading-notes)

# Module 06b discussion

## Title: Computer Architecture and Logic

Some of the primative datatypes in javascript are as follows.

1. Numbers - JavaScript has only one type of numbers.
Numbers can be written with, or without decimals:
Example: var x = 34; or var x = 34.00;
2. Booleans - Booleans can only have two values: true or false.
var x = 3;
var y = 3;
var z = 4;
(x == y)       // Returns true
(x == z)       // Returns false
3. Arrays - JavaScript arrays are written with square brackets. Array items are separated by commas.
var fruit = ['Apple', 'Orange'];
4. Objects - JavaScript objects are written with curly braces {}. Object properties are written as name:value pairs, separated by commas.
Example:
var person = x = {firstName:'Pete', lastName:'Margellos'};
5. Undified - In JavaScript, a variable without a value, has the value undefined. The type is also undefined.
Example:
var fruit;    // Value is undefined, type is undefined
6. Null - In JavaScript null is "nothing". It is supposed to be something that doesn't exist. Unfortunately, in JavaScript, the data type of null is an object. You can consider it a bug in JavaScript that typeof null is an object. It should be null. You can empty an object by setting it to null:
Example:
var fruit = ['Apple', 'Orange'];
fruit = null;    // Now value is null, but type is still an object

You can check the type of operator that you are using with the typeof operator.
The typeof operator returns a string indicating the type of the unevaluated operand.
Example: 
1. console.log(typeof 1); output would be > "number"
2. console.log(typeof 'ball'); output would be > "string"
3. console.log(typeof true); output would be > "boolean"
4. console.log(typeof undeclaredVariable); output would be > "undefined"
5. console.log(typeof x = {firstName:'Pete', lastName:'Margellos'); output would be > > Object { firstName: 'Pete', lastName: 'Margellos' }

JavaScript evaluates expressions from left to right. Different sequences can produce different results:
var x = 10 + 10 + "='Help';
Results: 20Help