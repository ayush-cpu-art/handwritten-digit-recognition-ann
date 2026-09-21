# ✍️ Handwritten Digit Recognition using Artificial Neural Networks

## 📌 Overview

This project implements a handwritten digit recognition system using an Artificial Neural Network (ANN) built with TensorFlow/Keras.

The model is trained on the MNIST handwritten digit dataset to classify images of digits from **0 to 9**.

---

## 🎯 Objective

- Load and explore the MNIST dataset.
- Preprocess and normalize image data.
- Build an Artificial Neural Network.
- Train the model using TensorFlow/Keras.
- Evaluate the model using classification metrics and a confusion matrix.
- Visualize training accuracy and loss.

---

## 📊 Dataset

**Dataset:** MNIST Handwritten Digits Dataset

The dataset contains grayscale images of handwritten digits ranging from **0 to 9**.

> The dataset is not included in this repository.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn

---

## ⚙️ Methodology

1. Load the MNIST dataset.
2. Explore the dataset.
3. Check for missing values.
4. Separate features and labels.
5. Normalize pixel values.
6. Convert labels using one-hot encoding.
7. Build the ANN architecture.
8. Train the model for 10 epochs.
9. Evaluate the model.
10. Visualize training performance.

---

## 🧠 Model Architecture

| Layer | Configuration |
|---|---|
| Input Layer | 784 Features |
| Hidden Layer 1 | 128 Neurons — ReLU |
| Hidden Layer 2 | 64 Neurons — ReLU |
| Output Layer | 10 Neurons — Softmax |

### Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Metric:** Accuracy
- **Epochs:** 10

---

## 📈 Results

The project includes visualizations for evaluating the ANN:

- Training Accuracy
- Training Loss
- Confusion Matrix
- Sample Digit Prediction

The model demonstrates the ability of a feed-forward neural network to learn patterns from handwritten digit images.

---

## 📂 Project Structure

```text
Handwritten-Digit-Recognition-ANN/
│
├── images/
│   ├── sample_digit.png
│   ├── accuracy.png
│   ├── loss.png
│   └── confusion_matrix.png
│
├── handwritten_digit_recognition_ann.ipynb
├── README.md
├── requirements.txt
└── .gitignore