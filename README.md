# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The bug occurs when the program attempts to access an element in an array using an index that is out of the valid range (0 to array.length - 1).  This example showcases the error and provides a solution.

## How to reproduce

1. Compile `bug.java`
2. Run the compiled program
3. Observe the `ArrayIndexOutOfBoundsException`

## Solution

The solution (`bugSolution.java`) corrects the loop condition to prevent accessing the invalid index.