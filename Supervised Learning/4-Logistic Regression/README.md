# Logistic Regression Model for Telco Customer Churn Prediction

## Overview

This repository contains a logistic regression model aimed at predicting customer churn for a telecommunications company using the Telco Customer Churn dataset. Logistic regression is utilized here as a binary classifier to forecast whether a customer will churn based on their service usage and demographic information.

## Logistic Regression: Theoretical Foundation

### What is Logistic Regression?

Logistic Regression is a statistical method for predicting binary outcomes from data by using a logistic function to model a binary dependent variable. In the context of machine learning, it is considered a special case of linear regression that is specifically used for classification purposes.

### Mathematical Model

The logistic function, also known as the sigmoid function, is defined as follows:
\[ \sigma(z) = \frac{1}{1 + e^{-z}} \]
where \( z \) is the input to the function, typically the dot product of weights and input features. This function maps any real-valued number into the (0, 1) interval, which can be interpreted as a probability.

### Model Estimation

The parameters of logistic regression are typically estimated using maximum likelihood estimation (MLE). This method seeks to find the parameter values that maximize the likelihood of the observed sample.

## Applications

### Predicting Customer Churn

In this project, logistic regression is used to predict whether a customer will churn based on various features such as monthly charges, tenure, service additions, and demographic factors.

### Benefits of Using Logistic Regression

- **Interpretability**: It provides the significance of each feature on the prediction.
- **Efficiency**: Requires less computational resources as compared to more complex models.
- **Probability Estimates**: Outputs a probability score that reflects the likelihood of an occurrence, providing more nuanced insights into the predictions.

## Repository Structure

- `data/`: This folder contains the Telco Customer Churn dataset.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model building.
- `src/`: Source code for the logistic regression model and utilities.
- `README.md`: Provides a detailed overview of the project, model, and instructions.

## How to Use This Repository

1. **Data Preparation**: Load the Telco Customer Churn dataset and preprocess the data as described in the notebooks.
2. **Model Training**: Run the logistic regression model to fit the data.
3. **Evaluation**: Assess the model's performance using accuracy, precision, recall, and ROC curves.
4. **Prediction**: Utilize the model to predict churn on new customer data.
