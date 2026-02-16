# Perceptron From Scratch

Implementation of a binary linear classifier built entirely from first principles using only NumPy.  
This project recreates the perceptron learning algorithm step-by-step without using any machine learning libraries.

---

## Project Overview

The perceptron is one of the earliest supervised learning algorithms and the foundation of modern neural networks.  
This notebook demonstrates how a linear classifier learns a decision boundary through iterative weight updates driven by misclassification.

The implementation includes:

- manual weight and bias initialization  
- custom training loop  
- perceptron update rule  
- prediction function  
- decision boundary visualization  

---

## Repository Structure

Perceptron/
│
├── Perceptron.ipynb # full implementation and experiments
└── README.md

---

## Algorithm

For each training sample:


Where:

- w → weight vector  
- b → bias  
- x_i → feature vector  
- y_i ∈ {−1, +1}  

Training continues until either:

- no misclassifications remain, or  
- maximum epochs reached  

---

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Run all cells sequentially
3. Observe training convergence and decision boundary

---

## Results

The perceptron successfully learns a linear decision boundary on linearly separable data.

Example outcomes:

- Converges within few epochs  
- Achieves perfect classification on separable dataset  
- Fails on non-linearly separable data (expected limitation)

---

## Key Learning Points

This implementation builds intuition for:

- linear classification geometry  
- mistake-driven learning  
- neural network weight updates  
- limitations of linear models  

---

## Limitations

- Works only for linearly separable data  
- No probabilistic output  
- No margin optimization  
- Sensitive to feature scaling  

---

## Author

Arman Mahmud  
CSE Undergraduate — Machine Learning
