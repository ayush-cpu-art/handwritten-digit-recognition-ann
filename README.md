# ✍️ Handwritten Digit Recognition using Artificial Neural Networks

A handwritten digit recognition system built using an **Artificial Neural Network (ANN)** with **TensorFlow/Keras**. The model is trained on the **MNIST handwritten digit dataset** to classify images of digits from **0 to 9**.

---

## 📌 Overview

This project demonstrates an end-to-end image classification workflow using a feed-forward neural network.

The model processes handwritten digit images, learns patterns from pixel values, and predicts the corresponding digit class.

---

## 🎯 Objectives

- Load and explore the MNIST dataset.
- Perform data preprocessing and normalization.
- Prepare labels using one-hot encoding.
- Build an Artificial Neural Network using TensorFlow/Keras.
- Train the model for 10 epochs.
- Evaluate classification performance.
- Analyze model performance using accuracy, loss, confusion matrix, and classification metrics.

---

## 📊 Dataset

### MNIST Handwritten Digits Dataset

The project uses the **MNIST dataset**, containing grayscale images of handwritten digits from **0 to 9**.

The dataset is not included in this repository.

**Dataset source:**  
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## 🧠 Model Architecture

The ANN consists of:

| Layer | Configuration |
|---|---|
| Input Layer | 784 input features |
| Hidden Layer 1 | 128 neurons, ReLU |
| Hidden Layer 2 | 64 neurons, ReLU |
| Output Layer | 10 neurons, Softmax |

### Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Metric:** Accuracy
- **Epochs:** 10

The 784 input features correspond to the flattened **28 × 28 pixel** representation of each MNIST image.

---

## ⚙️ Methodology

```text
MNIST Dataset
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Pixel Normalization
      ↓
One-Hot Encoding
      ↓
ANN Architecture
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Performance Visualization
