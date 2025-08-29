# MNIST Handwritten Digit Recognition using ANN

This project implements a basic **Artificial Neural Network (ANN)** to classify handwritten digits from the **MNIST dataset**.  
The dataset used here has a shape of **(42000, 785)** where:  
- 784 columns represent pixel values of 28×28 grayscale images.  
- 1 column represents the digit label (0–9).  

The goal of this project is to demonstrate the end-to-end process of **data preprocessing, model building, training, evaluation, and prediction** using TensorFlow/Keras.

---

## 📂 Dataset
- **Source**: MNIST (commonly available in Keras, or as CSV with labels included).  
- **Training Samples**: 42,000  
- **Image Size**: 28×28 pixels (flattened into 784 features).  
- **Classes**: 10 (digits 0–9).  

---
## Model Architecture
- Input Layer: 784 neurons (flattened 28×28 image)
- Hidden Layer 1: Dense(128), activation = ReLU
- Hidden Layer 2: Dense(64), activation = ReLU
- Hidden Layer 3: Dense(128), activation = ReLU
- Output Layer: Dense(10), activation = Softmax

## 📊 Results
Training Accuracy: ~99.07%
Validation Accuracy: ~96.83%
Test Accuracy: ~96.51%

