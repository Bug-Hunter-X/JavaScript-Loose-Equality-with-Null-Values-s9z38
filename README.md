# JavaScript Loose Equality with Null Values

This repository demonstrates a common subtle bug in JavaScript related to the use of loose equality (==) with null values.  The provided code demonstrates the bug and shows how to fix it.

## Bug Description:
The original code uses loose equality (==) to check if input values are null. Loose equality can lead to unexpected behavior when dealing with null values and other types. This can result in incorrect calculations or unexpected outputs.

## Solution:
The solution provides a corrected version that uses strict equality (===) to resolve the issue. Strict equality is generally preferred over loose equality, especially when dealing with null or undefined values, as it prevents unexpected type coercion.