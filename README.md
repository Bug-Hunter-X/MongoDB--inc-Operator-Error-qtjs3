# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value results in unexpected behavior.

## Bug
The provided code attempts to increment a field by the string "1". This will not result in an increment, but rather replace the field's value. 

## Solution
The solution involves correctly providing a numerical value to the `$inc` operator, thereby incrementing the numerical field as expected.
