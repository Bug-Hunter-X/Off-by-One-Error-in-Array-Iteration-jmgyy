# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.

The `bug.java` file contains code with the error.  The `bugSolution.java` file provides the corrected code.

This error can lead to `ArrayIndexOutOfBoundsException` which can be difficult to trace in large programs. Always ensure your loop conditions properly handle the boundaries of the array.