# MNIST Digit Classifier (NumPy Only)

A simple neural network built from scratch using NumPy to classify handwritten digits from the MNIST dataset. This project demonstrates the core mechanics of neural networks including forward propagation, backpropagation, and weight updates without relying on deep learning frameworks.

---

## Features

- Neural Network implemented with NumPy only (no TensorFlow, PyTorch, etc.)
- Custom forward and backward propagation
- Trains and tests on CSV version of the MNIST dataset
- Saves learned weights to a JSON file
- Visualizes predictions on random test samples
---
## Installation & Setup
1. Clone the Repository
```bash
git clone https://github.com/sodahiya/MINST-Classification
```
2. Install Dependencies
```bash 
pip install -r requirements.txt
```
3. Run
```bash
main.ipynb
```
4. Open predictor.html with a live server
---
## Neural Network Architecture
TrainLatest.csv: 60,000 training samples  
TestLatest.csv: 10,000 test samples  
Input Layer: 784 nodes (28x28 pixels)  
Hidden Layer: Configurable (default: 16 neurons) with ReLU activation  
Output Layer: 10 neurons (digits 0–9) with Softmax activation

---
## Preview
![Screenshot 2025-06-16 201328](https://github.com/user-attachments/assets/546db769-a289-4a64-a4a9-96a608ffc4ab)
![Predicitons](https://github.com/user-attachments/assets/8acddd89-6e17-4e86-a610-f54c88b189a1)

