# Simple Neural Network in PyTorch

This project demonstrates the creation, training, and visualization of a simple feedforward neural network using PyTorch. It covers all the essential steps, from defining the model to training it with mini-batches and visualizing the results.

## Overview

- **Model Architecture**: A simple neural network with:
  - Input Layer: 2 features
  - Hidden Layer: 3 neurons with ReLU activation
  - Output Layer: 1 neuron
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Stochastic Gradient Descent (SGD)

## Key Features

1. **Model Definition**:
   - The network `SimpleNN` is defined using PyTorch's `nn.Module`.
   - Includes a forward pass for predictions.

2. **Training Process**:
   - Loss computation with backpropagation.
   - Weight updates using the optimizer.
   - Mini-batch processing with PyTorch's `DataLoader`.

3. **Visualization**:
   - **Loss Curve**: Tracks training progress.
   - **Predictions vs. Targets**: Compares model predictions to ground truth.
   - **Weight Distribution**: Visualizes weights for each layer.
