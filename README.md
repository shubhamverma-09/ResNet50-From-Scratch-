# ResNet-50 from Scratch

A complete implementation of **ResNet-50** built from scratch using **TensorFlow/Keras**, without relying on pre-trained weights. This project recreates the original deep residual architecture and demonstrates how residual learning enables the effective training of very deep convolutional neural networks.

---

## 📌 Project Overview

ResNet (Residual Network) introduced skip connections to address the degradation and vanishing gradient problems encountered in deep neural networks. By learning residual mappings instead of direct mappings, deeper architectures can be optimized more efficiently.

In this project, the ResNet-50 architecture is implemented entirely from scratch and trained on the **CIFAR-10** dataset.

---

## ✨ Features

* Complete ResNet-50 implementation from scratch
* Identity and convolutional residual blocks
* TensorFlow/Keras-based training pipeline
* Data preprocessing and augmentation
* Training on the CIFAR-10 dataset
* Visualization of training and validation metrics
* Modular and well-documented code

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Dataset

The model is trained and evaluated on the **CIFAR-10** dataset, which contains 60,000 color images across 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

Dataset Split:

* Training Images: 50,000
* Test Images: 10,000

---

## 🧠 Model Architecture

The implemented ResNet-50 follows the original residual learning framework and consists of:

* Initial Convolution Layer
* Residual Stages with Identity Blocks
* Convolutional Blocks for Dimension Matching
* Batch Normalization
* ReLU Activations
* Global Average Pooling
* Fully Connected Classification Layer

---

## 🚀 Training Configuration

* Dataset: CIFAR-10
* Epochs: 50
* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metrics: Accuracy
* Data Augmentation: Enabled

---

## 📊 Results

The repository includes:

* Training Accuracy Curve
* Validation Accuracy Curve
* Training Loss Curve
* Validation Loss Curve

The final performance demonstrates the effectiveness of residual learning even when training deep architectures from scratch.

---

## 📁 Repository Structure

```text
├── ResNet50.ipynb
├── README.md
├── accuracy_curve.png
├── loss_curve.png
```

---


## 🎯 Learning Outcomes

Through this project, you will learn:

* How ResNet-50 is designed internally
* The role of residual connections
* Why skip connections improve optimization
* How to train deep CNNs from scratch
* Best practices for image classification workflows

---

