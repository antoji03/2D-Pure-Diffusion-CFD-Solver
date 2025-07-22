# 2D Pure Diffusion CFD Solver

This project implements a 2D Finite Volume Method (FVM) solver for the steady-state diffusion equation using Python.
It compares numerical results with the analytical solution and evaluates the accuracy through relative error metrics.

## Features

- Discretization via FVM on a uniform mesh for the steady-state diffusion equation using Python
- Gauss-Seidel and Gauss-Seidel SOR solvers implemented from scratch in Python
- Analytical solution for validation of the Numerical Model
- Matplotlib visualizations
- Execution time and memory consumption analysis

## Project Structure

- `code/` — Python and MATLAB scripts for the solver and analytical solution
- `figures/` — Plots comparing numerical and analytical results
- `2D_Pure_Diffusion_CFD_Code_Report.pdf` — Project report, with detailed explanation of the proposed case and results analysis

## How to Run

- To run the code, download or clone the repository and navigate to the `code/` folder.

There are three different solver implementations:

- **Mark I** – Direct solver using matrix inversion 
- **Mark II** – Iterative Gauss-Seidel solver 
- **Mark III** – Iterative Gauss-Seidel SOR solver with relaxation 

Each script can be executed independently. Results are printed to the terminal and visualized using matplotlib.

## Author

António Reis  
MSc Aerospace Engineering — Aerodynamics | CFD | Numerical Methods  
🔗 [LinkedIn](www.linkedin.com/in/antónio-reis-615471327)
