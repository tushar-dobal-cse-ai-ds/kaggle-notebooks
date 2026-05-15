# 🏥 Disease Prediction System using Machine Learning

## 🚀 Overview

This project focuses on predicting diseases based on patient symptoms using machine learning techniques.

The system analyzes symptom patterns and predicts the most likely disease while also providing:
- Disease descriptions
- Recommended precautions
- Feature importance insights

The project demonstrates how machine learning can support healthcare decision-making and early disease identification. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objective

To build a machine learning-based healthcare system capable of:
- Predicting diseases from symptoms
- Providing disease-related information
- Suggesting precautions for patients
- Supporting healthcare decision systems

---

## 📊 Dataset

Dataset Source:
- [Kaggle Disease Prediction Dataset](https://www.kaggle.com/code/tushardobal/disease-prediction-system-using-machine-learning/input?utm_source=chatgpt.com)

Dataset Files Used:
- `dataset.csv`
- `symptom_Description.csv`
- `symptom_precaution.csv`
- `Symptom-severity.csv`

Dataset Characteristics:
- Multi-class disease classification
- Symptom-based features
- Balanced disease distribution
- Structured symptom-disease relationships

---

## 🧠 Machine Learning Workflow

### 🔹 Data Preprocessing

- Column cleaning
- Missing value handling
- MultiLabel symptom transformation
- Binary symptom encoding
- Label encoding for diseases

---

### 🔹 Feature Engineering

Symptoms were converted into binary features using:
- `MultiLabelBinarizer`

This preserved patient-level symptom information and enabled effective machine learning modeling.

---

### 🔹 Models Used

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Results

### Model Performance

| Model | Accuracy |
|---|---:|
| Decision Tree | 100% |
| Random Forest | 100% |
| XGBoost | 100% |

### Important Observation

The dataset is highly structured and deterministic, where diseases correspond to unique symptom combinations.

This leads to near-perfect separability between classes and extremely high accuracy.

In real-world healthcare systems, symptom overlap and noisy data would make the task significantly more challenging.

---

## 🧬 Advanced Features

### ✅ Disease Description System

Provides detailed disease explanations using:
- `symptom_Description.csv`

### ✅ Precaution Recommendation System

Suggests preventive actions using:
- `symptom_precaution.csv`

### ✅ Feature Importance

Identifies the most influential symptoms for prediction using XGBoost feature importance.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---
