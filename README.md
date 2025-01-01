# Uninitialized Pointer Bug in C
This repository demonstrates a common error in C programming: using an uninitialized pointer.  The provided code compiles but may exhibit unpredictable behavior depending on the system's memory allocation.

## Bug Description
The `bug.c` file contains a C program that attempts to dereference an uninitialized pointer. This can lead to a segmentation fault, unexpected values, or other erratic behavior.

## Solution
The `bugSolution.c` file offers a corrected version of the code.  It demonstrates proper pointer initialization before dereferencing.