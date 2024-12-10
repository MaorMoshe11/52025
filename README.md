# Neural Networks Homework - PS1

## Overview
This repository contains the solutions for the Neural Networks Homework (PS1). The tasks involve implementing and experimenting with neural networks using custom layers and functions for forward and backward propagation. The assignments explore foundational concepts in machine learning and neural networks, including:
- Building and training custom neural networks.
- Understanding backpropagation and autograd.

---

## Files in the Repository

### 1. **PS1_Part2_Hello_NN_2024_ID_311118780.ipynb**
- **Purpose**: Implements a custom neural network for the MNIST dataset.
- **Contents**:
  - Construction of a fully connected feedforward neural network with:
    - Input Layer
    - Two hidden layers with ReLU activation
    - Output Layer with Softmax activation
  - Training the model on the MNIST dataset using cross-entropy loss.
  - Testing the network's performance.

### 2. **PS1_Part3_Autograd_2024_ID_311118780.ipynb**
- **Purpose**: Explores the implementation of automatic differentiation for gradient calculations.
- **Contents**:
  - Implementation of custom backpropagation algorithms.
  - Verification of gradients with respect to network parameters.
  - Comparison of manual backpropagation with standard autograd tools.

---

## Neural Network Details
The network is designed for the MNIST dataset (handwritten digits classification):
1. Input layer processes image pixels (28x28 dimensions flattened to a vector).
2. Hidden layers employ the ReLU activation function to learn non-linear relationships.
3. The output layer uses Softmax for multi-class classification.

### Loss Function:
- **Cross-Entropy Loss**: Used for training a classification model with multiple classes.

### Optimizer:
- Custom backpropagation logic was implemented to compute parameter updates.

---

## How to Use

1. Open the Jupyter Notebooks in your preferred environment:
   - `PS1_Part2_Hello_NN_2024_ID_311118780.ipynb`
   - `PS1_Part3_Autograd_2024_ID_311118780.ipynb`
2. Run the cells sequentially to train and test the model.

---

## Results

- **Accuracy**: The network achieves a competitive accuracy on the MNIST test set.
- **Gradients**: Verified the correctness of gradients computed manually against autograd results.

---

## Future Improvements

- Implement dropout layers for regularization.
- Experiment with different activation functions (e.g., Leaky ReLU, Tanh).
- Extend the network to handle more complex datasets beyond MNIST.
