# Neural Network From Scratch

A modular deep learning framework built completely from scratch using Python and NumPy without relying on external machine learning libraries like TensorFlow or PyTorch.

This project implements the core internals of neural networks including forward propagation, backpropagation, activation functions, optimizers, regularization techniques, dropout, and learning rate scheduling.

---

# Features

## Core Neural Network Components

* Dense (Fully Connected) Layers
* Forward Propagation
* Backward Propagation
* He Weight Initialization
* Bias Handling

---

## Activation Functions

* ReLU
* Softmax

---

## Loss Functions

* Categorical Cross Entropy
* Combined Softmax + Cross Entropy optimization

---

## Regularization

* L1 Regularization
* L2 Regularization
* Dropout Layer

---

## Optimizers

* SGD (Stochastic Gradient Descent)
* SGD with Momentum
* Nesterov Accelerated Gradient (NAG)
* AdaGrad
* RMSProp
* Adam

---

## Learning Rate Techniques

* Learning Rate Decay
* ReduceLROnPlateau Scheduler

---

## Model Training Utilities

* Custom Training Loops
* Validation Evaluation
* Accuracy Tracking
* Loss Tracking

---

# Concepts Implemented

This project demonstrates the implementation of:

* Matrix-based neural network computations
* Chain rule and gradient propagation
* Numerical stability in Softmax
* Optimizer internals
* Gradient-based learning
* Regularization techniques
* Training stabilization methods

---

# Project Structure

```plaintext
Neural-Network-from-scratch/
│
├── backprop.ipynb
├── complete_nn.ipynb
├── weight_and_bias.ipynb
├── README.md
```

---

# Technologies Used

* Python
* NumPy
* Matplotlib
* NNFS Dataset Utilities

---

# Example Dataset

The project currently uses the spiral dataset from the NNFS dataset utilities for multi-class classification experiments.

---

# Example Training Output

```python
epoch: 0, loss: 1.098, accuracy: 0.360
epoch: 100, loss: 0.756, accuracy: 0.673
epoch: 500, loss: 0.321, accuracy: 0.913
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/Ritik4259/Neural-Network-from-scratch.git
```

Move into the project directory:

```bash
cd Neural-Network-from-scratch
```

Install dependencies:

```bash
pip install numpy matplotlib nnfs
```

---

# Running the Project

Run:

Open using VS code, colab or Jupyter notebook and run the cells

---

# Future Improvements

* Batch Normalization
* Mini-Batch Gradient Descent
* CNN Layers
* Model Serialization (Save/Load)
* K-Fold Cross Validation
* Configurable Model API
* GPU Support
* C++ Backend Integration

---

# Learning Goals

This project was built to deeply understand:

* how neural networks work internally
* how gradients flow through layers
* how optimization algorithms improve training
* how modern deep learning frameworks operate internally

---

# Key Takeaway

Instead of only using high-level ML frameworks, this project focuses on implementing and understanding the mathematical and computational foundations of deep learning systems from scratch.

---


GitHub: [Ritik4259](https://github.com/Ritik4259?utm_source=chatgpt.com)
