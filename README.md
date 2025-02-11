# C++ Vector Out-of-Bounds Access Bug

This repository demonstrates a common C++ error: accessing an element in a `std::vector` beyond its allocated bounds.  This leads to undefined behavior, often resulting in crashes or unexpected program behavior.  The solution shows how to avoid this error using size checks or safer container methods.

## Bug
The `bug.cpp` file contains code that attempts to access an element in a `std::vector` outside its valid range.  This is a classic off-by-one error.

## Solution
The `bugSolution.cpp` file provides a corrected version, ensuring all vector accesses are within bounds.