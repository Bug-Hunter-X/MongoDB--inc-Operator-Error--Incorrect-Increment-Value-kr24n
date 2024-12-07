# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value instead of a numerical value will result in an error or unexpected behavior.

## Bug Description
The `$inc` operator expects a numerical value to increment a field. Using a string value leads to an incorrect update or an error, as shown in the `bug.js` example.

## Solution
The correct solution is to provide a numerical value to the `$inc` operator, ensuring proper field increment behavior as demonstrated in `bugSolution.js`
