# Function approximation (TMA4215 Numerical Mathematics, NTNU)

Individual project, autumn 2026. The notebook (in Norwegian) implements and compares classical methods for approximating a function from samples:

- **Lagrange interpolation** with equidistant and Chebyshev nodes, the Runge phenomenon, and error bounds
- **Piecewise interpolation**: convergence rates and measured run times compared with global interpolation
- **Radial basis functions (RBFs)**: the trade-off between accuracy and conditioning controlled by the shape parameter
- **Optimised nodes**: gradient descent with backtracking and automatic differentiation (autograd) to place the nodes and choose the shape parameter

Open `function_approximation.ipynb` to see the code, plots and discussion.

Requirements: Python 3, NumPy, matplotlib, autograd.
