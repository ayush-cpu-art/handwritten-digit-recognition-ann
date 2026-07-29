# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## 📌 Overview

This project implements a Handwritten Digit Recognition system using an Artificial Neural Network (ANN) built with TensorFlow/Keras. The model is trained on the MNIST dataset to classify handwritten digits (0–9).

This project was developed as part of AI-ML Assignment 8.

---

## 🎯 Objective

- Load and explore the MNIST dataset.
- Perform data preprocessing.
- Build an Artificial Neural Network.
- Train the model using TensorFlow/Keras.
- Evaluate model performance using accuracy, confusion matrix, and classification report.
- Visualize training accuracy and loss.

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits Dataset

Kaggle:
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

> **Note:** The dataset is not included in this repository. Please download it from the above link.

---

## 🛠️ Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn

---

## ⚙️ Methodology

1. Load the dataset.
2. Explore the dataset.
3. Check for missing values.
4. Separate features and labels.
5. Normalize pixel values.
6. Convert labels using One-Hot Encoding.
7. Build an ANN consisting of:
   - Input Layer
   - Hidden Layer (128 neurons, ReLU)
   - Hidden Layer (64 neurons, ReLU)
   - Output Layer (10 neurons, Softmax)
8. Train the model for 10 epochs.
9. Evaluate the model.
10. Visualize model performance.

---

## 🧠 Model Architecture

| Layer | Configuration |
|--------|---------------|
| Input Layer | 784 Features |
| Hidden Layer 1 | 128 Neurons (ReLU) |
| Hidden Layer 2 | 64 Neurons (ReLU) |
| Output Layer | 10 Neurons (Softmax) |

Optimizer:
- Adam

Loss Function:
- Categorical Crossentropy

Metric:
- Accuracy

---

## 📊 Results

The ANN successfully classified handwritten digits from the MNIST dataset with high accuracy.

Evaluation includes:

- Test Accuracy
- Confusion Matrix
- Classification Report
- Accuracy vs Epoch Graph
- Loss vs Epoch Graph

---

## 📁 Project Structure

```
Handwritten-Digit-Recognition-ANN/
│
├── data/
│   ├── mnist_train.csv
│   └── mnist_test.csv
│
├── images/
│   ├── sample_digit.png
│   ├── accuracy.png
│   ├── loss.png
│   └── confusion_matrix.png
│
├── Assignment-8.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run:

```bash
jupyter notebook Assignment-8.ipynb
```

---

## 📌 Conclusion

Artificial Neural Networks are effective for handwritten digit recognition tasks. Hidden layers help the model learn complex patterns from image data, leading to high classification accuracy. Although ANNs require considerable computational resources and training data, they outperform many traditional machine learning techniques for image classification problems.

---

## 👨‍💻 Author

**Ayush Dev**