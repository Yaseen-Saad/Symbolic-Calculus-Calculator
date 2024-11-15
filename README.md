# Symbolic-Calculus-Calculator

## Description
This is a simple Python GUI application built using `tkinter` and `sympy` for symbolic mathematical computations. The tool allows users to compute derivatives and integrals (both definite and indefinite) of mathematical expressions.

## Features
- Calculate derivatives of mathematical expressions.
- Compute indefinite integrals of expressions.
- Compute definite integrals with user-defined bounds.
- User-friendly GUI for entering expressions, variables, and bounds.

## Requirements
- Python 3.x
- `sympy` library

## Installation
1. Clone or download this repository.
2. Install the required Python library:
   ```bash
   pip install sympy
   ```
3. Run the application:
  ```bash
  python symbolic_math_tool.py
  ```
## Usage
1. Enter a mathematical expression (e.g., `x**2 + 3*x`).
2. Specify the variable with respect to which the operation is to be performed (e.g., `x`).
3. Select the desired operation:
 - **Integral**: Computes the integral of the expression. Specify bounds for definite integrals or leave them blank for an indefinite integral.
 - **Derivative**: Computes the derivative of the expression.
4. (Optional) Enter lower and upper bounds for definite integrals.
5. Click the Calculate button to perform the operation.
6. The result will be displayed in the text area.
## Example
Expression: `x**2`
Variable: `x`
Operation: Derivative
Result: `d/dx(x**2) = 2*x`
Notes:
- Use Python's mathematical syntax for expressions (e.g., ** for power, sin(x) for sine).
 - The tool supports symbolic computation for any variable and expression supported by the sympy library.
## Author
[Yaseen Saad]
