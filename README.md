# MongoDB $inc operator type error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation. The `$inc` operator is used to increment a numerical field by a specified value. However, in this example, a string value is provided instead of a number, resulting in an error.

The solution involves correcting the data type of the increment value to be a number.