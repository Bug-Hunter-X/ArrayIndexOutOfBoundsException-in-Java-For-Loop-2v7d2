# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException` caused by incorrect loop bounds.

The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

## Bug Description
The bug occurs in the first for loop. The loop condition `i <= arr.length` allows the loop to run one iteration too many, attempting to access an index that is out of bounds for the array.

## Solution
The solution is simple: change the loop condition to `i < arr.length` to ensure the loop terminates before attempting to access any index beyond the array's valid range.