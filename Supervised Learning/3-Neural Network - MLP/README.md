# Multi-Layer Perceptron (MLP) for Sentiment Analysis

## Overview

This project utilizes a Multi-Layer Perceptron (MLP), a type of artificial neural network, to perform sentiment analysis on the IMDB movie reviews dataset. The objective is to classify reviews as positive or negative, demonstrating the capability of MLPs to handle complex natural language processing tasks.

## Theoretical Foundation

### What is a Multi-Layer Perceptron?

A Multi-Layer Perceptron (MLP) is a class of feedforward artificial neural network that includes one or more layers of hidden nodes, in addition to input and output layers. MLPs are capable of capturing complex relationships in data by learning a series of weighted sums and non-linear transformations.

### Core Components

- **Input Layer**: Accepts feature data.
- **Hidden Layers**: Intermediary processing layers that use weights and biases to learn from data. MLPs can have one or multiple hidden layers.
- **Output Layer**: Produces the final predictions of the network.
- **Activation Functions**: Functions like ReLU or Sigmoid that introduce non-linearity to the learning process, enabling the model to learn more complex patterns.

### Learning Process

MLPs use a method known as backpropagation for learning — they iteratively adjust the weights of connections by calculating the gradient of the loss function with respect to each weight via the chain rule.

## Applications

While this project focuses on sentiment analysis, MLPs are broadly applicable in numerous fields including:

- **Image Recognition**: Classifying images and recognizing patterns.
- **Speech Processing**: Understanding spoken language.
- **Financial Forecasting**: Predicting stock movements and identifying financial trends.
- **Medical Diagnosis**: Analyzing patient data to diagnose diseases.

## Repository Structure

- `data/`: Directory containing the IMDB Dataset.
- `scripts/`: Python scripts for training and evaluating the MLP model.
- `notebooks/`: Jupyter notebooks with exploratory data analysis and step-by-step instructions.
- `README.md`: This file, providing an overview and guide to the repository.
