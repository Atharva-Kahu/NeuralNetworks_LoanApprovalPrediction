
# Loan Approval Prediction Using Neural Networks

This project predicts whether a loan will be approved based on applicant data using binary classification models built in TensorFlow/Keras.

## 📌 Project Overview

This notebook explores a binary classification problem using a deep learning approach. It includes two models:

1. **Model 1**: A simple neural network built using Keras.
2. **Model 2**: A hyperparameter-tuned model using Keras Tuner (Hyperband).

Early stopping and validation loss monitoring are implemented to avoid overfitting.

## 📂 Dataset

The dataset includes applicant financial and personal details such as:
- Income
- Education
- Loan intent and amount
- Credit history
- Home ownership
- Past defaults

## 🧠 Model Architecture

- Input Layer: Feature vector
- Hidden Layers: Dense layers with ReLU or Tanh activation
- Output Layer: Dense(1) with Sigmoid activation

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- Keras Tuner
- Scikit-learn
- Matplotlib

## 📊 Model Evaluation

- Accuracy, Precision, Recall, and F1 Score
- Confusion Matrix
- Precision-Recall Curve
- Loss & Accuracy vs Epoch plots

## 🚀 How to Run

1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Run the notebook:
```bash
jupyter notebook Loan_Approval_Prediction.ipynb
```
