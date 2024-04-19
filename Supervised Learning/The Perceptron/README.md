# The Perceptron Algorithm

## Overview

The Perceptron is a fundamental type of artificial neural network and one of the oldest algorithms used in supervised learning. It serves as the building block for more complex neural network structures. This README provides an overview of the Perceptron algorithm, including its theory, applications, and a guide to the accompanying Jupyter Notebook implementation.

## Theoretical Background

The Perceptron algorithm, introduced by Frank Rosenblatt in 1957, is a binary classifier that learns the weights to be assigned to inputs to make a decision whether an input vector belongs to one class or another. It is based on a linear predictor function combining a set of weights with the feature vector. The algorithm updates these weights iteratively through a simple learning rule, adjusting them based on the error made in previous predictions.

### Learning Rule

The learning process involves adjustments made to the weights according to the following rule:

w = w + η (y - ŷ) x

where `w` represents the weights, `η` is the learning rate, `y` is the true label, `ŷ` is the predicted label, and `x` is the input features.

## Applications

The Perceptron is particularly useful in fields that require binary classification tasks, such as:

- Email spam detection
- Image classification
- Sentiment analysis
- Biometric identification

Despite its simplicity, the Perceptron forms the foundation for understanding more complex neural networks used widely in deep learning today.

## Implementation Guide

The accompanying Jupyter Notebook (`Perceptron.ipynb`) includes a detailed implementation of the Perceptron algorithm using the Diabetes Dataset. The notebook covers:

- Data preprocessing
- Model initialization and training
- Evaluation of the model on test data
- Visualization of the decision boundaries
