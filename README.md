# Python Scalar Autograd Engine

A Python implementation of an automatic differentiation (autograd) engine focused on scalar operations, designed specifically for neural network training. Built from the ground up with simplicity and educational purposes in mind.

## Overview

This project implements a scalar autograd engine that can:
- Track and store variable data in mathematical operations
- Compute gradients automatically through backpropagation
- Support basic neural network operations
- Visualize computation graphs

## Project Structure

The project is organized into two main components:

- `engine.py`: Contains the core autograd functionality
  - Implementation of the `Value` class for scalar operations
  - Support for basic operations (+, -, *, /, power)
  - Implementation of activation functions (ReLU)
  - Backpropagation capabilities

- `neural_network.py`: Contains the neural network implementation
  - Neural network architecture
  - Training utilities
  - Network optimization

## Detailed Documentation

A comprehensive explanation of the project (in Spanish) can be found in the [notes notebook](./notebook/notes.ipynb), which includes:
- Detailed explanations of the autograd engine implementation
- Mathematical foundations and derivations
- Usage examples and visualizations
- Neural network training demonstrations
