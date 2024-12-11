# Unexpected String Concatenation in JavaScript

This repository demonstrates a common error in JavaScript: unexpected string concatenation when adding a number and a string.

## The Bug
The `bug.js` file contains a function `foo` that attempts to add two numbers. However, when a number and a string are passed as arguments, the function unexpectedly concatenates the number and the string rather than throwing an error or performing a numerical addition. This occurs because JavaScript performs type coercion implicitly, converting the number to a string before concatenation.

## The Solution
The `bugSolution.js` file provides a solution that addresses this issue using explicit type checking and conversion, ensuring that the function performs numerical addition or throws an error when incompatible types are used. This is important for preventing unexpected behavior and improving code robustness.