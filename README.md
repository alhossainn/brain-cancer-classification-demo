# Brain Cancer Classification Using CNNs (PyTorch)

This project demonstrates how to classify brain cancer using Convolutional Neural Networks (CNNs). It includes both a **custom-built CNN** and a **pre-trained CNN** implementation using PyTorch.

> ⚠️ **Note**: This project is intended as a **showcase of my code** for educational and reference purposes. It is designed to help others understand and learn from the implementation rather than to achieve high-end or state-of-the-art performance. Extensive hyperparameter tuning or advanced data augmentation is **not** performed.

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle:

- **Dataset**: [Brain Cancer - Multi Cancer Dataset](https://www.kaggle.com/datasets)
- **Local Path Used**: `/kaggle/input/multi-cancer/Multi Cancer/Multi Cancer/Brain Cancer`
- **Classes**:
  - `brain_glioma`
  - `brain_menin`
  - `brain_tumor`
- **Total Images per Class**: 5,000
- **Split Ratio**:
  - Train: 70%
  - Validation: 15%
  - Test: 15%

## 🧠 Model Architectures

Two models are implemented:

### 1. Custom CNN
A custom convolutional neural network built from scratch using PyTorch, with:
- Multiple convolutional layers
- ReLU activation
- MaxPooling
- Fully connected layers

### 2. Pre-trained CNN
A transfer learning approach using a pre-trained model `ResNet50`. The final classification layer is modified for 3 output classes.
