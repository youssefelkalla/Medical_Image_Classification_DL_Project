# # Medical Image Classification using Deep Learning
## Chest X-Ray Pneumonia Detection

This project implements a Deep Learning-based Medical Image Classification system for detecting Pneumonia from Chest X-Ray images using Convolutional Neural Networks (CNNs) in PyTorch.

The project was developed as part of a Deep Learning course project.

---

# Project Overview

Pneumonia is a serious lung infection that can be detected through Chest X-Ray imaging. The goal of this project is to build and evaluate CNN models capable of classifying Chest X-Ray images into:

- NORMAL
- PNEUMONIA

The project includes:
- Data preprocessing
- Data augmentation
- CNN model development
- Training and validation
- Overfitting reduction
- Performance visualization
- Model evaluation

---

# Dataset

Dataset Name:
Chest X-Ray Images (Pneumonia)

Dataset Link:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Dataset Description:
- Medical Chest X-Ray images
- Binary classification problem
- Classes:
  - NORMAL
  - PNEUMONIA

---

# Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- KaggleHub
- Google Colab

---

# Data Preprocessing

The following preprocessing techniques were applied:

- Image resizing
- Normalization
- Random horizontal flipping
- Random rotation
- Random affine transformations
- Data augmentation

---

# CNN Architectures

## 1. Baseline CNN
A simple CNN model consisting of:
- Convolutional layers
- ReLU activations
- MaxPooling layers
- Fully connected layers

## 2. Improved CNN
An enhanced CNN model including:
- Batch Normalization
- Dropout
- Weight Decay
- Improved architecture design
- Overfitting reduction techniques

---

# Overfitting Reduction Techniques

Several techniques were used to reduce overfitting:

- Data augmentation
- Dropout regularization
- Batch normalization
- Weight decay
- Reduced model complexity
- Dataset re-splitting

---

# Results

## Final Test Results

| Model | Accuracy | Loss |
|---|---|---|
| Improved CNN | 79.97% | 0.4800 |

---
# Results Visualizations

Training and validation curves are included inside the `results` folder of the repository.

The repository contains:
- Accuracy curves
- Loss curves
- Training performance visualizations

# Observations

- The improved CNN achieved stable learning behavior.
- Overfitting was significantly reduced after applying regularization techniques and improving dataset splitting.
- Training and validation curves became more consistent and smooth.

---

# Project Structure

```bash
Medical-Image-Classification-DL/
│
├── Medical_Image_Classification_Project.ipynb
├── README.md
├── requirements.txt
│
├── results/
│   ├── accuracy_curve.png
│   └── loss_curve.png
