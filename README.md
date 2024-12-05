# Ada Off-by-One Error Example

This repository demonstrates a common off-by-one error in Ada programming.  Ada arrays are 1-based, meaning the first element is at index 1, not 0 as in languages like C or Python.

The `bug.ada` file contains code that incorrectly accesses an array element at index 0, leading to a `Constraint_Error`. The corrected version is in `bugSolution.ada`.