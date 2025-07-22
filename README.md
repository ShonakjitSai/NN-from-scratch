# Building-a-Neural-Network-from-scratch
# Neural Network From Scratch — XOR Classifier

This project implements a simple feedforward neural network **entirely from scratch** using **NumPy** — no high-level ML libraries like TensorFlow or PyTorch.

### 🔍 Problem
Learn the XOR logic gate, a classic non-linearly separable problem.

### 🧠 Architecture
- Input: 2 features (+1 bias term)
- Hidden layer: 2 neurons with `tanh` activation
- Output layer: 1 neuron with `sigmoid` activation
- Manual forward pass, backpropagation, and gradient descent

### 📦 Contents
- `nn_from_scratch.ipynb`: Jupyter Notebook version
- `nn_from_scratch.py`: Python script version
- `README.md`: Project overview

### 📊 Training Example
- Input: 4 combinations of XOR truth table
- Output: 0 or 1
- Learns using stochastic gradient descent (SGD)

### ✅ Key Highlights
- Manual weight initialization
- Manual forward/backward propagation
- Derivative math implemented explicitly
- No external ML frameworks — 100% NumPy

### 💡 Future Work
- Extend to multiclass classification
- Add loss/accuracy visualization
- Make network depth configurable
