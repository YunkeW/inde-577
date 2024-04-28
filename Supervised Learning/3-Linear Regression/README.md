# Linear Regression Analysis

## Introduction

This subdirectory contains the linear regression analysis performed on the `Salary_dataset.csv`. The primary focus is to model and predict salaries based on years of experience using linear regression, a foundational algorithm in statistics and machine learning.

## Linear Regression Algorithm

Linear regression is a predictive modeling technique for quantifying the relationship between one or more predictor variables (independent variables) and a continuous outcome variable (dependent variable). The algorithm assumes a linear relationship between the inputs and the target.

### Theoretical Foundation

- **Equation**: The model is based on the linear equation `y = β0 + β1X1 + ... + βnXn + ε`, where `y` is the target, `β0` is the intercept, `β1,...,βn` are the coefficients, `X1,...,Xn` are the features, and `ε` is the error term.
- **Least Squares**: The method of least squares is used to estimate the coefficients by minimizing the sum of the squares of the residuals (the differences between observed and predicted values).

### Assumptions

The algorithm relies on several assumptions, including:

- Linearity: The relationship between the independent and dependent variables is linear.
- Independence: The residuals are independent across observations.
- Homoscedasticity: The residuals have constant variance at every level of the independent variables.
- Normality: The residuals are normally distributed.

## Applications

Linear regression is widely applied in various fields such as:

- Economics: Predicting GDP, employment rates, etc.
- Finance: Stock prices forecasting.
- Medicine: Estimating risks or effects of treatments.
- Real estate: Housing price estimation.
