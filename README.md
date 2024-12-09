# MongoDB $inc operator error with string value
This example demonstrates an error that can occur when using the MongoDB $inc operator with a string value instead of a numerical value.
The `$inc` operator in MongoDB is used to increment a numerical field by a specified value.  It expects a number; providing a string will result in an error.  This example shows the incorrect usage and how to correct it.

## Bug Report:
The original code attempts to increment the 'age' field by '1' (a string), causing an error.  The correct approach is to increment using a number (1).