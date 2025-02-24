# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The example code attempts to access an array element beyond its valid index range, causing a runtime exception.

## Bug Description

The `BuggyArray.java` file contains a `for` loop that iterates one time too many, exceeding the array's valid index range of 0-4. Attempting to access `arr[5]` throws an exception.

## Solution

The `FixedArray.java` file demonstrates the correct way to iterate over an array, ensuring that the loop condition prevents accessing invalid array indices.