# Heart Disease Prediction — Capstone Machine Learning Project

## 📌 Project Overview
This repository contains the **Week 4 Major Capstone Project** focused on building an end-to-end clinical decision support model to predict the likelihood of heart disease in patients using the **UCI Heart Disease Dataset**.

---

## 🛠️ Complete Machine Learning Pipeline

1. **Data Preprocessing & Cleaning**:
   * Imputed missing continuous feature values using median statistics and missing categorical values using modal frequency[cite: 13].
   * Converted multiclass disease severity indicators (`num` column) into a binary target (`0` = Absence, `1` = Presence)[cite: 13].
2. **Feature Engineering & Scaling**:
   * Applied `get_dummies` for One-Hot Encoding categorical features (`chest pain`, `resting ecg`, `thal`, etc.)[cite: 13].
   * Scaled numerical variables using `StandardScaler` to ensure uniform feature magnitude[cite: 13].
3. **Model Development**:
   * Trained and evaluated **Logistic Regression** and **Decision Tree Classifier**[cite: 13].
4. **Performance Metrics & Evaluation**:
   * Measured Accuracy, Precision, Recall, F1-Score, Confusion Matrices, and ROC-AUC Curves[cite: 13].

---

## 📊 Model Evaluation Results

| Metric | Logistic Regression | Decision Tree Classifier |
| :--- | :--- | :--- |
| **Accuracy** | **84.24%** | 78.26% |
| **Precision** | **84.11%** | 80.39% |
| **Recall** | **88.24%** | 80.39% |
| **ROC-AUC Score** | **0.91** | 0.83 |

---

## 🚀 How to Run locally

1. **Clone Repository**:
   ```bash
   git clone [https://github.com/mahima5080/Heart-Disease-Prediction-Capstone.git](https://github.com/mahima5080/Heart-Disease-Prediction-Capstone.git)
   cd Heart-Disease-Prediction-Capstone
