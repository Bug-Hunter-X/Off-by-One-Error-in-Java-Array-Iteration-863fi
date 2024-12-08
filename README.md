# Off-by-One Error in Java Array Iteration
This repository demonstrates a common off-by-one error in Java that occurs when iterating over an array. The error arises from an incorrect loop condition that accesses an index beyond the array's bounds, resulting in an ArrayIndexOutOfBoundsException.

## Description
The provided Java code attempts to populate an integer array with even numbers. However, the for loop's condition `i <= arr.length` causes an error because valid indices range from 0 to `arr.length - 1`.  The corrected code uses `i < arr.length` to avoid this issue.

## Solution
The solution involves modifying the loop condition to correctly iterate within the bounds of the array.