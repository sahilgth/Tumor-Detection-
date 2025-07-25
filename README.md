# Tumor-Detection-
Tumor Detection Using Machine Learning

This project applies various machine learning algorithms to classify tumors as **benign** or **malignant** based on features extracted from digitized images of breast masses (Breast Cancer Wisconsin Diagnostic dataset).

## 📌 Problem Statement

Breast cancer is among the leading causes of death among women worldwide. Early detection using machine learning techniques can significantly reduce diagnosis time and improve outcomes. This project builds predictive models to assist in tumor classification.

---

## 📂 Dataset

- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**: 30 numeric parameters (e.g., radius, texture, concavity)
- **Target**: `Diagnosis` — `M` (Malignant) or `B` (Benign)

---

## 📊 Exploratory Data Analysis (EDA)

- Correlation matrix to identify related features
- Distribution plots for feature comparison
- Class balance check

---

## 🤖 Models Implemented

- Logistic Regression
- Random Forest
- Support Vector Machine
- k-Nearest Neighbors

---

## ✅ Evaluation Metrics

- Accuracy
- Precision / Recall / F1-Score
- ROC-AUC
- Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## 📈 Feature Importance

The most influential features were:
- `worst concave points`
- `worst perimeter`
- `mean concavity`
