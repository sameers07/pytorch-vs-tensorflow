# pytorch-vs-tensorflow

This repository contains comparisons and implementations of various deep learning models built using PyTorch and TensorFlow.

## Core PyTorch Components

Here is a beginner's guide to the main modules imported in PyTorch:

### 1. `import torch`
* **Purpose:** The core PyTorch engine.
* **What it does:** It handles **Tensors** (multidimensional arrays that can run on GPUs) and all basic mathematical operations. It is the foundation for your data and mathematical computations.

### 2. `import torch.nn as nn`
* **Purpose:** The Neural Network module.
* **What it does:** It provides pre-built building blocks or **layers** (like Linear, Convolutional, Recurrent layers), activation functions (like ReLU, Sigmoid), and loss functions (like MSELoss, CrossEntropyLoss) to structure your neural network.

### 3. `import torch.optim as optim`
* **Purpose:** The Optimizer module.
* **What it does:** It contains **optimization algorithms** (like SGD, Adam, RMSprop) that update your model's weights during training based on the calculated gradients to minimize error/loss.

