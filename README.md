# TensorFlow Assignment 2

This repository contains the source code for the TensorFlow Assignment 2 completed as part of the coursework.

## 👤 Student Information
- **Name:** Senthil Kumar Ramamoorthy
- **University:** University of Central Missouri
- **Program:** MS in Data Science and Artificial Intelligence

## 📂 Assignment Overview

### ✅ Task 1: Tensor Operations & Reshaping
- Performed basic tensor operations using TensorFlow
- Used `tf.reshape()` to manipulate tensor shapes
- Demonstrated broadcasting and arithmetic operations

### ✅ Task 2: Loss Function Comparison
- Implemented Mean Squared Error (MSE) and Categorical Cross Entropy (CCE)
- Compared both loss functions using sample predictions
- Visualized results using a bar chart (Matplotlib)

### ✅ Task 3: Neural Network with TensorBoard Logging
- Trained a simple neural network on MNIST dataset
- Logged training progress with TensorBoard
- Visualized training and validation accuracy/loss

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Execute each cell step by step
3. For Task 3, launch TensorBoard using:
   ```python
   %load_ext tensorboard
   %tensorboard --logdir logs/fit
