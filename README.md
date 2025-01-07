# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution. The error occurs when attempting to access the 'length' property of an undefined variable.

## The Bug
The `bug.js` file contains a function that calculates the length of an array or returns 0 if the input is null. However, it fails to handle the case where the input is undefined, resulting in a `TypeError`.

## The Solution
The `bugSolution.js` file demonstrates how to fix this error by adding a check for the undefined case before accessing the 'length' property.  This makes the function more robust and prevents unexpected errors.

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment (e.g., browser's console, Node.js).
3. Execute the code in each file to see the error and the solution in action.