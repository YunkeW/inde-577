# Gradient Descent Algorithm

## Overview

This repository section is dedicated to the Gradient Descent algorithm, one of the most popular optimization algorithms in machine learning and statistics. It is designed to minimize a cost function by iteratively moving towards the minimum value of the function, guided by the negative of the gradient.

## Theoretical Foundation

Gradient Descent is based on the observation that if the multi-variable function \( F(x) \) is defined and differentiable in a neighborhood of a point \( a \), then \( F(x) \) decreases fastest if one goes from \( a \) in the direction of the negative gradient of \( F \) at \( a \), \( -\nabla F(a) \). It involves calculations of the gradient of the cost function with respect to the parameters at each step, and updating the parameters in the direction that results in the steepest descent.

### Algorithm Steps

1. **Initialize Parameters**: Start with initial guesses for the parameters to be optimized.
2. **Compute the Gradient**: Calculate the gradient of the cost function concerning each parameter.
3. **Update Parameters**: Adjust the parameters in the direction of the negative gradient.
4. **Repeat**: Continue the process until the cost function converges to a minimum.

## Applications

- **Linear Regression**: In machine learning, it is often used to find the best-fitting line in linear regression.
- **Logistic Regression**: Used for training logistic regression models in classification tasks.
- **Neural Networks**: Fundamental in backpropagation while training neural networks.

## Dataset Used

The Boston Housing Dataset is employed to demonstrate the application of the Gradient Descent algorithm. It contains the following features:

- `CRIM`: Per capita crime rate by town
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS`: Proportion of non-retail business acres per town.
- `...`
- `MEDV`: Median value of owner-occupied homes in $1000's (Target Variable)

The goal is to predict the median value of houses (`MEDV`) based on the features provided.

## Implementation

The `Gradient_Descent.ipynb` notebook within this subdirectory contains the Python code implementation of the Gradient Descent algorithm, along with a detailed walkthrough of using it on the Boston Housing Dataset to predict housing prices.
