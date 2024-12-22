# Null Handling in JavaScript Function

This repository demonstrates a common error in JavaScript function handling of null values. The function `foo` is supposed to perform an operation, however, it does not handle `null` inputs correctly.

## Bug Description

The original `foo` function is missing robust handling for `null` values passed as arguments. This leads to unexpected behavior or errors when called with null arguments, which might not be caught during testing unless specifically checked for.

## Solution

The solution is to explicitly check for `null` values at the beginning of the function, returning an appropriate value (in this case `null`) or throwing an error if null values are not expected.

## How to reproduce

1.  Clone this repository.
2.  Run `node bug.js` to observe the buggy behavior.
3.  Run `node bugSolution.js` to see the corrected version.
