# Handling Null Values in JavaScript

This repository contains a simple JavaScript function that demonstrates a common approach to handle null values to prevent unexpected behavior in arithmetic operations.

The `bug.js` file contains a function that performs addition on two numbers but also handles the case where either number might be null by returning null if either input is null. This avoids errors that could occur if null values are treated as 0.  The `bugSolution.js` file contains the same function but with this null-handling improvement. 

## How to Run

1.  Clone this repository.
2.  Open `bug.js` and `bugSolution.js` in a text editor or IDE.
3.  Open your browser's developer console or use `node bug.js` (if node.js is installed) to run the code and see the output.  Observe how null values are handled gracefully.

This is a basic example but it's a common practice to protect your code against unexpected null values.