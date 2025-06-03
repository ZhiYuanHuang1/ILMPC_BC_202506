# ILMPC_BC_202506
Anti-pitching of high-speed multihull ship based on fast predictive control and iterative learning control
# MATLAB Ship Motion Control Simulation

This repository contains MATLAB simulations for ship motion control using an Improved Linear Model Predictive Control (IL-MPC) algorithm. The implementation compares uncontrolled ship motion with the proposed IL-MPC controller in wave disturbance conditions.

## Repository Contents

### 📁 Main Programs (`*.m` files)
Core MATLAB code implementing simulations for:
- Uncontrolled system
- The proposed IL-MPC algorithm
- Result analysis and visualization

### 🌊 Wave Disturbance Data (`*.mat` files)
Sample wave disturbance input data used in the simulations

### ⚙️ Runtime Environment
The code was developed and tested using **MATLAB R2019b**. Using this version or a compatible later version is recommended to ensure consistent results.

## Code Output
Executing the provided code will generate the following key results:

### 1. Comparison Plots
[Heave Displacement]
[Pitch Angle]
[Control Inputs]

- **Heave displacement time history**: Uncontrolled vs. IL-MPC
- **Pitch angle time history**: Uncontrolled vs. IL-MPC
- **Control input time history** (T-foil and flap) under IL-MPC

### 2. Numerical Results (Output to Command Window):

Average single-step computation time of the IL-MPC controller.

Root Mean Square (RMS) values of Heave displacement:
- Uncontrolled case
- IL-MPC controlled case

Root Mean Square (RMS) values of Pitch angle:
- Uncontrolled case
- IL-MPC controlled case
