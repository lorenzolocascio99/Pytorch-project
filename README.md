# Pytorch-project

Problem Description: You are given a dataset generated from a cubic polynomial function with added noise. Your task is to use PyTorch to estimate the coefficients of this polynomial.

Data Generation:

Input x: 1000 points evenly spaced between -100 and 100

Output y: Generated using y = ax³ + bx² + cx + d + ε

Noise term ε: Random values from normal distribution with small but unknown variance

The coefficients a, b, c, and d are unknown

The dataset is saved in polynomial_data.csv

Your Tasks:

Use PyTorch to estimate the coefficients (parameters) of this cubic polynomial:

Coefficient of x³ (a)

Coefficient of x² (b)

Coefficient of x (c)

Constant term (d)

Implement:

A suitable loss function

Parameter optimization using gradient descent

Visualize:

Plot the original data points

Plot your fitted curve

Report:

Your estimated coefficients

How well your estimated curve fits the original data

Final loss value
