# Incorrect Return Value in Comparison Function

This repository demonstrates a common coding error in Python: an incorrect return value in a comparison function.

The `my_function` compares two numbers and intends to return the larger one. However, due to the structure of the `if` and `else` statements, the function only considers the larger value. The error is that the `else` block returns the value `b`, which is not always the correct larger value.

The solution provided correctly returns the larger of two numbers.