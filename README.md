# Steepest Descent Algorithm with Secant Method Subroutine for Line Search

This repository contains a Python implementation of the steepest descent algorithm combined with a secant method subroutine for line search. The code also includes testing for convergence based on a gradient threshold stopping criterion.

## Problem Description

The algorithm solves the following objective function:

$$
f(x_1, x_2, x_3) = (x_1 - 4)^4 + (x_2 - 3)^2 + 4(x_3 + 5)^4
$$

with the steepest descent method, and the stopping criterion is defined as:

$$
\|\|\nabla f(x^{(k)})\|\| \leq \epsilon, \quad \epsilon = 10^{-6}.
$$

### Steps Included:
- A Python routine that runs the steepest descent algorithm with a secant method for line search.
- Testing the algorithm on different initial points and evaluating the number of iterations required to satisfy the stopping criterion.
- Evaluating the objective function at the final point to check how close it is to zero.

## Files in the Repository
- **Secant_Line_Search_implementation.ipynb**: A colab file for running the routine.
- **README.md**: (this file) Documentation on how to run the code and understand its functionality.

## How to Run the Code

### Prerequisites
To run this code, you need Python 3.x installed on your machine. The required libraries are:

- NumPy

You can install the required dependencies by running:

```bash
pip install numpy
```



