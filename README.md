# MongoDB $inc Operator Type Error
This example demonstrates an uncommon error in MongoDB when using the `$inc` operator with an incorrect data type.  The `$inc` operator is designed to increment a numeric field. Providing a string will not result in the expected behavior. The solution shows the correct way to use `$inc` with a numeric value.

## Bug
The `bug.js` file contains the incorrect usage of `$inc`, leading to a potential type error or unexpected update behavior. 

## Solution
The `bugSolution.js` file provides the corrected implementation, incrementing the field using a proper numeric value.