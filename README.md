# Handwritten Digit Classification using ANN

## Overview
This project utilizes an Artificial Neural Network (ANN) to classify handwritten digits (0-9) from the MNIST dataset. The ANN architecture includes layers with ReLU activation functions and a Softmax output layer for multi-class classification. It achieves an accuracy of 97.5% on the test dataset.

## Architecture
The neural network architecture consists of:
- Input layer: 784 nodes (corresponding to 28x28 pixel images flattened)
- Hidden layers: Multiple layers with ReLU activation
- Output layer: 10 nodes with Softmax activation (one for each digit class)

## Training
The model is trained using:
- Loss function: Sparse categorical cross-entropy
- Optimizer: Adam optimizer with default parameters
- Metrics: Accuracy

## Graphs
During training, graphs are generated to visualize:
- Training and validation loss over epochs
- Training and validation accuracy over epochs

