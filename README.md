# MongoDB $inc Operator Error
This example demonstrates an incorrect use of the MongoDB `$inc` operator, leading to an error.
The `$inc` operator is designed to increment a numerical field by a specified value.  Attempting to increment with a string value will result in an error.

**Solution:**  Always provide a numerical value to the `$inc` operator.
