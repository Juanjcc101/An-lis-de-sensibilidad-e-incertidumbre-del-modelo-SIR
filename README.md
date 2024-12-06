# Sensitivity and Uncertainty Analysis of the SIR Model

This repository contains the files and report for the project on control and sensitivity and uncertainty analysis of a nonlinear dynamic system with input, specifically the SIR (Susceptible-Infectious-Recovered) model. Below, the repository contents and the report sections in IMRAD format are detailed.

## Repository Contents

### IMRAD Report

- **Live Script File**: `Trabajo2_SL_Final.mlx`
  - Contains the results of the project presented in IMRAD format. Results from various tests can be executed and presented from this file.

### State Feedback Control

- **Simulink File**: Contains the Simulink model used for state feedback control.

### Sensitivity and Uncertainty Analysis

- **Simulink File**: Contains the Simulink model used for sensitivity analysis.
- **Information File**: Contains additional information and details about the sensitivity analysis.
- **GSUA File**: Contains the MATLAB code for sensitivity and uncertainty analysis using the GSUA tool.

## IMRAD Report Sections

### Introduction

A brief introduction to the problem, the SIR model, and the importance of sensitivity and uncertainty analysis in nonlinear dynamic systems.

### Mathematical Model and Description

Describes the mathematical model of the SIR system, including the input, output, and state variables, as well as the model parameters.

### Hypotheses

Outlines the hypotheses posed for the analysis and control of the SIR model.

### Methods

- **Verified Model in Simulink**: Includes the verification of the SIR model in Simulink, which serves as input for subsequent analysis.
- **Tests and Simulations**: Details the calculations and mathematical models used in each test and simulation, with emphasis on the mathematical aspects and the use of MATLAB and Simulink software.
- **Summary of Steps**: Summarizes the procedure followed for conducting sensitivity and uncertainty analysis.

### Results

- **Linear State Feedback Control**: Designed and simulated a linear control system using pole placement based on state feedback for a selected equilibrium point. Includes:
  - Plotting the linearity curve.
  - Selection of an equilibrium point of interest.
  - Linearization at the operating point.
  - Comparison between the linear approximation and the nonlinear model.
  - Controllability analysis of the linear model.
  - Controller design and closed-loop system simulation.
  - Analysis of system response under input disturbances.

- **Uncertainty Analysis**: Program and plots for the uncertainty analysis of the process output with the controller and disturbances.

- **Scalar Sensitivity Analysis**: Plots for the scalar sensitivity analysis to rank the model parameters from most to least sensitive using the GSUA tool.

### Discussion

Interpretation of the results obtained from the sensitivity and uncertainty analysis, as well as the design of the linear state feedback control.
