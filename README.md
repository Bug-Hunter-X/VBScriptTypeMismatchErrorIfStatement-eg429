# VBScript Type Mismatch Error in If Statement

This repository contains a simple VBScript function that demonstrates a type mismatch error. The error occurs when comparing non-numeric values in an If statement.

## Bug

The `f` function compares two values, `a` and `b`. If `a` and `b` are not numeric values, a type mismatch error will occur. This is because the comparison operators (`>`, `<`, `=`) in VBScript require numeric operands. 

## Solution

The solution is to explicitly check the data types of `a` and `b` before performing the comparison. If either value is not numeric, you should handle the error appropriately (e.g., display a message, convert the values to numeric types, etc.).