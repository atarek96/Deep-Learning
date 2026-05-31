# MNIST Digit Classification with ANN & CNN

A comparative implementation of **Artificial Neural Network (ANN)** and **Convolutional Neural Network (CNN)** for handwritten digit recognition using the MNIST dataset.

## 📋 Project Overview

This project demonstrates the difference in performance between a simple fully connected neural network and a convolutional neural network on the classic MNIST dataset. The goal is to classify handwritten digits (0-9) with high accuracy.

### Key Objectives:
- Build and train an ANN model
- Build and train a CNN model
- Compare performance metrics (Accuracy, Precision, Recall, F1-Score)
- Visualize training performance

## 🛠 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Pandas & NumPy**
- **Matplotlib** (for visualization)
- **Scikit-learn** (for evaluation metrics)

## 📊 Dataset

- **MNIST Handwritten Digits Dataset**
- 60,000 training images
- 10,000 test images
- 28x28 grayscale images

## 📈 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| ANN   | 97.84%   | 97.83%    | 97.84% | 97.83%   |
| **CNN**   | **99.16%**   | **99.17%**    | **99.15%** | **99.16%**   |

CNN significantly outperforms the ANN, as expected for image classification tasks.

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/mnist-ann-cnn.git
cd mnist-ann-cnn
