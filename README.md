# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript involving the incorrect handling of null values and provides a corrected version.

The `bug.js` file shows the faulty code.  The `bugSolution.js` file demonstrates how to address the issue.

## Bug Description

The original function `foo` fails when provided with null values as it doesn't perform appropriate type checking or null value handling, leading to unexpected behavior or errors.  The improved solution explicitly checks for null values and handles them gracefully.