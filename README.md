This repository contains a Python program demonstrating a common error in recursive functions: stack overflow.  The `function` recursively calculates the factorial of a number. When the input number is very large, the program will encounter a `RecursionError`. The solution demonstrates a more robust method using iteration to avoid stack overflow issues.