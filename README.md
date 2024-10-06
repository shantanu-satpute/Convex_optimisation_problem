
# Convex Optimization for Factory Location
## Project Introduction:

**1**. **Problem statement**:

The goal of this project is to minimize transportation costs by finding the optimal locations for factories relative to fixed warehouses. The challenge lies in positioning the factories such that the overall transportation cost between factories and warehouses, as well as between factories themselves, is minimized. This optimization problem is solved using convex optimization techniques, and the results are visualized using Matplotlib..

**2**. **Introduction to Convex Optimization:**:

Convex optimization is a subfield of optimization where the objective is a convex function, and the feasible region is a convex set. This project utilizes cvxpy to perform convex optimization by minimizing transportation costs, represented as a weighted sum of Euclidean distances between the locations of warehouses (fixed points) and factories (variable points).

**3**. **Tools used**:

1. Python: The main programming language used for the project.

2. CVXPY: A Python library for convex optimization, used to solve the optimization problem.

3. NumPy: Used for numerical operations and random weight generation.

4. Matplotlib: Used for visualizing the results by plotting the positions of warehouses and factories.

## Project outline:
1. Fixed and Variable Points: Fixed points represent warehouse locations with known coordinates, while variable points (factories) are optimized based on transportation costs.

2. Weight Generation: Randomly generated weights represent transportation costs between warehouses and factories.

3. Cost Function and Optimization: The cost function minimizes the weighted sum of Euclidean distances, and the convex optimization is performed using cvxpy.

4. Visualization: The optimal locations of factories are visualized using Matplotlib.

## References:

1. CVXPY Documentation: https://www.cvxpy.org/

2. Matplotlib Documentation: https://matplotlib.org/


## Future Ideas:

1. Add more constraints or cost metrics to the optimization problem.

2. Use real-world datasets for transportation costs.


