# 🧠 Breast Cancer Classification with a Simple Neural Network

This project implements a **deep learning model** using a simple Neural Network (NN) to classify breast cancer tumors as **malignant** or **benign** based on features provided in the **Breast Cancer Wisconsin Diagnostic Dataset**, available via `sklearn.datasets.load_breast_cancer()`.

## 📊 Dataset

We use the built-in dataset from **Scikit-learn**, which includes 569 samples with 30 numeric features. The target is binary:
- `0`: Malignant (cancerous)
- `1`: Benign (non-cancerous)

### Features
Some of the 30 features include:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness
... and more statistical values for each tumor.

## 🧪 Problem Statement

Classify whether a tumor is malignant or benign based on its features using a **simple feedforward neural network**.

---

## 🛠️ Tech Stack

- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras (for Neural Network)
- Matplotlib / Seaborn (for visualization)
