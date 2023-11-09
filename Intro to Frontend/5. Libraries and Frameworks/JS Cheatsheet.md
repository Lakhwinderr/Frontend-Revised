
# JavaScript Syntax Cheatsheet

A quick reference guide for JavaScript syntax.

## Comments
```javascript
// Single-line comment

/*
Multi-line comment
*/
```

## Variables
```javascript
let variableName = value; // Declare a variable
const constantName = value; // Declare a constant
```

## Data Types
```javascript
let number = 42; // Number
let text = "Hello, World!"; // String
let isTrue = true; // Boolean
let array = [1, 2, 3]; // Array
let object = { key: "value" }; // Object
let undefinedVar; // Undefined
let nullVar = null; // Null
```

## Operators
```javascript
let sum = 5 + 3; // Addition
let difference = 7 - 2; // Subtraction
let product = 4 * 6; // Multiplication
let quotient = 10 / 2; // Division
let remainder = 10 % 3; // Modulus (Remainder)
let isGreater = 8 > 5; // Greater than
let isEqual = 5 === "5"; // Strict equality
let isNotEqual = 7 !== 7; // Not equal
let andOperator = true && false; // Logical AND
let orOperator = true || false; // Logical OR
let notOperator = !true; // Logical NOT
```

## Conditional Statements
```javascript
if (condition) {
  // Code to execute if condition is true
} else if (anotherCondition) {
  // Code to execute if anotherCondition is true
} else {
  // Code to execute if neither condition is true
}
```

## Loops
```javascript
for (let i = 0; i < 5; i++) {
  // Code to repeat 5 times
}

while (condition) {
  // Code to execute while condition is true
}

do {
  // Code to execute at least once, then while condition is true
} while (condition);
```

## Functions
```javascript
function functionName(parameter1, parameter2) {
  // Code to execute when the function is called
  return result; // Optional return statement
}
```

## Objects and Methods
```javascript
let person = {
  name: "John",
  age: 30,
  sayHello: function() {
    console.log("Hello!");
  }
};

person.sayHello(); // Call a method
```

## Arrays
```javascript
let fruits = ["apple", "banana", "cherry"];
fruits[0]; // Access an element
fruits.length; // Get the number of elements
fruits.push("orange"); // Add an element to the end
fruits.pop(); // Remove the last element
```

## DOM Manipulation (Browser)
```javascript
document.getElementById("elementId"); // Get an element by ID
element.innerHTML = "New content"; // Modify inner HTML
element.style.color = "red"; // Change CSS styles
```

## Events
```javascript
element.addEventListener("click", function() {
  // Code to execute on click
});
```

## Error Handling
```javascript
try {
  // Code that may throw an error
} catch (error) {
  console.log(error.message);
} finally {
  // Code to execute regardless of errors
}
```

Use this cheatsheet as a quick reference for JavaScript programming.