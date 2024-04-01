# Multi-Layer Perceptron (MLP) Implementation

This repository contains an implementation of a Multi-Layer Perceptron (MLP) neural network in Python. The MLP is a type of artificial neural network composed of multiple layers of nodes, where each layer is fully connected to the next layer. It is capable of learning non-linear relationships between input and output data.

## Overview

The implementation includes the following components:
- MultiLayerPerceptron class: Defines the structure and behavior of the MLP.
- Activation functions: Sigmoid and hyperbolic tangent (tanh) functions are provided for the activation of hidden units.
- Training and prediction methods: fit(), predict(), forward(), and backward() methods are implemented for training and inference.

## Usage

To use the MLP implementation, follow these steps:

| Step   | Description                                                             | Command                                                                             |
|--------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| Step 1 | Install the required dependencies:                                      | pip install numpy                                                                  |
| Step 2 | Import the MultiLayerPerceptron class into your Python script:          | from mlp import MultiLayerPerceptron                                              |
| Step 3 | Create an instance of the MultiLayerPerceptron class with desired parameters: | mlp = MultiLayerPerceptron(learning_rate=0.1, num_input_features=2, num_hidden_units=2, num_output_units=1, activation_function='sigmoid') |
| Step 4 | Train the MLP on your dataset using the fit() method:                   | mlp.fit(X_train, y_train, num_epochs=100)                                          |
| Step 5 | Make predictions using the predict() method:                            | predictions = mlp.predict(X_test)                                                   |
