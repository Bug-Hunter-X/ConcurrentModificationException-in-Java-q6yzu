# ConcurrentModificationException in Java

This repository demonstrates a common error in Java: the `ConcurrentModificationException`.  The example shows how modifying a list while iterating over it using an enhanced for loop leads to this exception.  The solution provides a safe way to modify the list during iteration.

## Running the code

1. Clone this repository.
2. Compile and run `ConcurrentModificationExceptionExample.java`. This will throw the `ConcurrentModificationException`. 
3. Compile and run `ConcurrentModificationExceptionExampleSolution.java` to see a corrected version. 

## Related Resources

* [Oracle Documentation on ConcurrentModificationException](https://docs.oracle.com/javase/7/docs/api/java/util/ConcurrentModificationException.html)