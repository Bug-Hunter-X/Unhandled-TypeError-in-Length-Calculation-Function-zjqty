# Unhandled TypeError in Length Calculation Function

This repository demonstrates a common JavaScript error: a `TypeError` caused by incorrectly assuming an object has a `length` property.  The `bug.js` file contains the flawed function, while `bugSolution.js` provides a corrected version.

## Bug Description
The `foo` function attempts to access the `length` property of the input `x`.  This works fine for arrays and strings, but throws a `TypeError` if `x` is a number or `null`. This issue highlights the importance of robust input validation in JavaScript.

## How to reproduce
1. Clone this repository.
2. Run `node bug.js` in your terminal.