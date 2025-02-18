# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is used to increment or decrement a numeric field in a document.  The value provided to `$inc` must be a number; providing a string will result in an error.

**Bug:** Incorrect usage of the `$inc` operator.  A string is passed as the increment value instead of a number.

**Solution:** The solution shows the correct way of using the `$inc` operator by supplying a numerical value for the increment.
