# Aero Optimization using RF + GA for a AHMED BODY

This project uses Machine Learning + Optimization to minimize drag coefficient (Cd).

## Methods Used
- Random Forest (surrogate model)
- Genetic Algorithm (optimization)

##  Inputs
- alpha (angle)
- phi (parameter)

## Output
- Cd (Drag Coefficient)

## Objective
Minimize Cd by finding optimal alpha and phi.

## Workflow
1. Train Random Forest on dataset
2. Use Genetic Algorithm to explore input space
3. Run multiple GA iterations to find best solution

##  Tech Stack
- Python
- NumPy
- Scikit-learn

##  Result
GA successfully finds optimal parameters that minimize Cd.
