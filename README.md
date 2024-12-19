# Lua Function Parameter Nil Check Issue

This repository demonstrates a common error in Lua related to checking for `nil` function parameters and presents a solution.

The problem occurs when a function is called without providing a required parameter. If the function doesn't explicitly check for `nil`, it might attempt to perform operations on a `nil` value, causing an error.

The example showcases this issue and provides a corrected implementation.

## Solution

The solution focuses on explicitly checking the parameter for `nil` before attempting to perform any operations.