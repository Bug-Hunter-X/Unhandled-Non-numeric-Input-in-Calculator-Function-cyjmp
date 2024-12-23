# Unhandled Non-numeric Input in JavaScript Calculator

This repository demonstrates a common JavaScript error:  failure to handle non-numeric input in a mathematical function. The original `operate` function works correctly for basic arithmetic with numbers, but it crashes if you provide non-numeric values as input (strings, booleans, etc.).

The solution demonstrates how to robustly handle such situations by adding explicit input validation using `typeof` operator and `isNaN` function.

## How to Run

1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run `bug.js` and `bugSolution.js` in a JavaScript environment (like Node.js) and test with various numeric and non-numeric inputs.