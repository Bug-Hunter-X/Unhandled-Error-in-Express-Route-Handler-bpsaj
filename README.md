# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers:  lack of error handling for invalid input.

The `bug.js` file shows the problematic code.  It attempts to access a user by ID without checking if the ID is valid, which can cause errors if the ID is not a number.

The `bugSolution.js` file provides a corrected version with improved error handling to prevent unexpected crashes and return appropriate error responses.