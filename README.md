# deep-neural-network-image-classification
Implementation of a Deep L-Layer Neural Network from scratch using NumPy for binary image classification. The project builds and trains a cat vs. non-cat classifier with forward propagation, backward propagation, and model evaluation.
# 🧠 Deep Neural Network for Image Classification | Cat vs Non-Cat 🐱

This repository contains my implementation of a **Deep L-Layer Neural Network** from scratch using **NumPy** for **binary image classification**.  
The goal is to classify images as **cat** 🐱 or **non-cat** 🐶 using forward propagation, backward propagation, and gradient descent optimization.

---

## 🚀 Project Overview
This project focuses on implementing a **deep neural network** step by step **without using high-level frameworks** like TensorFlow or Keras.  
Key highlights include:
- Building and training a **deep L-layer neural network** from scratch.
- Using the **sigmoid** and **ReLU** activation functions.
- Implementing **forward propagation** and **backward propagation** manually.
- Testing the model with your own custom images.
- Achieving improved accuracy over a basic logistic regression implementation.

---

## 📌 Key Features
- 🔹 Implements a **Deep Neural Network** using only **NumPy**.
- 🔹 Supports **L-layer architectures** for better learning capacity.
- 🔹 Optimizes with **gradient descent**.
- 🔹 Trains on a labeled image dataset (**cats vs non-cats**).
- 🔹 Evaluates accuracy on both training and test sets.
- 🔹 Allows testing with your own custom images.

---

## 🧩 Model Architecture

| Layer | Type              | Activation |
|-------|--------------------|------------|
| Input | Image pixels      | -          |
| L1    | Fully Connected   | ReLU       |
| L2    | Fully Connected   | ReLU       |
| L3    | Fully Connected   | ReLU       |
| L4    | Fully Connected   | Sigmoid    |
| Output| Binary Prediction | 0 = Non-Cat / 1 = Cat |

<p align="center">
  <img src="https://i.imgur.com/gUbtHQk.png" alt="Deep Neural Network" width="650"/>
</p>

---

## 📂 Project Structure

```bash
deep-neural-network-image-classification/
│── data/                   # Dataset (cats vs non-cats)
│── notebooks/              # Jupyter notebook with implementation
│── images/                 # Test images for prediction
│── utils/                  # Helper functions for DNN
│── models/                 # Saved trained models
│── results/                # Accuracy curves & evaluation metrics
│── requirements.txt        # Project dependencies
└── README.md               # Documentation
