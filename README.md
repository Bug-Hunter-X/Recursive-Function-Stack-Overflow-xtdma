# Recursive Function Stack Overflow in Python
This repository demonstrates a common error in recursive functions: stack overflow for large inputs. The `bug.py` file contains a recursive function that calculates the sum of numbers from 1 to x. For large x, this leads to exceeding the maximum recursion depth causing a RuntimeError.

The `bugSolution.py` file shows how to fix this using iterative approach to avoid the stack overflow problem. 

## How to Reproduce
1. Clone this repository.
2. Run `bug.py` with large numbers. You will encounter a RuntimeError.
3. Run `bugSolution.py` with the same large numbers, it will complete successfully without the error.