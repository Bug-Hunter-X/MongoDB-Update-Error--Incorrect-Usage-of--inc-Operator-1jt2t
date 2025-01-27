# MongoDB Update Error: Incorrect Usage of $inc Operator

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a string value to `$inc` instead of a numeric value.

## Problem
The original code attempts to increment the 'field' by '1' (a string) which causes an error. The MongoDB shell will throw an error indicating an invalid operator.  Incorrect use of data types in MongoDB queries can lead to unexpected behavior and errors.