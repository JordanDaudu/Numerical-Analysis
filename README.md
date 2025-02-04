# Numerical Analysis in Python

<img src="Photos/numerical analysis.jpg" align="center" alt="logo" width="600" height="400">

This repository contains Python implementations of various numerical analysis methods, developed as part of the Numerical Analysis course at [SCE - Shamoon College of Engineering](https://www.sce.ac.il/).

## Table of Contents

- [Implemented Methods](#implemented-methods)
  - [1. Methods for Solving Linear Systems of Equations](#1-methods-for-solving-linear-systems-of-equations)
  - [2. Iterative Methods for Nonlinear Systems](#2-iterative-methods-for-nonlinear-systems)
  - [3. Interpolation and Polynomial Approximation](#3-interpolation-and-polynomial-approximation)
  - [4. Numerical Integration Methods](#4-numerical-integration-methods)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)

## Implemented Methods

### 1. Methods for Solving Linear Systems of Equations

- **1. Gauss Elimination**: A method to solve linear systems by transforming the system's matrix into an upper triangular form.
- **2. Gauss-Seidel Method**: An iterative technique to solve a square system of linear equations.
- **3. Jacobi Method**: An algorithm for determining the solutions of a diagonally dominant system of linear equations.

### 2. Iterative Methods for Nonlinear Systems

- **1. Bisection Method**: A root-finding method that repeatedly divides an interval in half and selects the subinterval in which the root exists.
- **2.Newton-Raphson Method**: An iterative method to find successively better approximations to the roots of a real-valued function.
- **3. Secant Method**: A root-finding algorithm that uses a sequence of roots of secant lines to approximate a root of a function.

### 3. Interpolation and Polynomial Approximation

- **1. Linear Interpolation**: A method of curve fitting using linear polynomials.
- **2. Polynomial Interpolation**: The interpolation of a given data set by a polynomial.
- **3. Lagrange Interpolation**: A form of polynomial interpolation based on the Lagrange basis polynomials.
- **4. Neville's Algorithm**: A recursive method for polynomial interpolation.
- **5. Cubic Spline Interpolation**: A form of interpolation where the interpolant is a piecewise cubic polynomial.

### 4. Numerical Integration Methods

- **1. Romberg Integration**: An extrapolation technique to improve the trapezoidal rule.
- **2. Simpson's Rule**: A method for numerical integration that approximates the integral of a function using parabolic segments.
- **3. Trapezoidal Rule**: Approximates the definite integral of a function by summing the areas of trapezoids under the curve.
- **4. Gaussian Quadrature**: A method of numerical integration that selects the optimal points and weights to approximate the integral of a function.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries: numpy, sympy

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/JordanDaudu/Numerical-Analysis.git
   cd Numerical-Analysis

