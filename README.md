# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion with the `+` operator.  JavaScript's dynamic typing can lead to unexpected behavior when mixing number and string operands.

## Bug Description
The `foo` function is intended to add two numbers. However, if a string is passed as an argument, the `+` operator performs string concatenation instead of numerical addition. This can lead to unexpected results and difficult-to-debug errors.

## Solution
The solution involves explicitly converting the operands to numbers using `parseInt()` or `Number()` before performing the addition. This ensures that the addition operation is performed numerically, regardless of the input types.