# 👨‍💼 Employee Attrition Prediction — HR Analytics Project

## 🚀 Overview

This project focuses on predicting employee attrition using machine learning techniques on HR analytics data.

The goal is to identify employees who are likely to leave the organization and uncover the major factors contributing to employee turnover. The project combines exploratory data analysis, feature engineering, classification models, and business insights to support HR decision-making.

---

## 🎯 Objective

To build a predictive machine learning system capable of identifying employees at risk of attrition while providing interpretable insights for workforce retention strategies.

---

## 📊 Dataset

Dataset Used:
- IBM HR Analytics Employee Attrition & Performance Dataset

Source:
- [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?utm_source=chatgpt.com)

Dataset contains:
- Employee demographics
- Job satisfaction metrics
- Work-life balance
- Overtime information
- Monthly income
- Department and job roles
- Attrition target variable

The IBM dataset is widely used for HR analytics and employee retention research. :contentReference[oaicite:1]{index=1}

---

## 🧠 Machine Learning Workflow

### 🔹 Data Preprocessing

- Data cleaning
- Label encoding
- Feature scaling
- Train-test split
- Feature selection

---

### 🔹 Exploratory Data Analysis

Analysis included:
- Attrition distribution
- Salary vs attrition
- Overtime impact
- Job satisfaction trends
- Work-life balance analysis

---

### 🔹 Models Used

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Results

### Final ROC-AUC Scores

| Model | ROC-AUC |
|---|---:|
| Logistic Regression | 0.8057 |
| Random Forest | 0.7935 |
| XGBoost | 0.7754 |

### Key Observation

Logistic Regression outperformed more complex ensemble models, indicating that employee attrition patterns were captured effectively using a simpler and more interpretable model.

This is especially valuable in HR analytics where explainability matters for decision-making.

---

## 📊 Key Business Insights

Major factors influencing attrition:

- Monthly Income
- Overtime
- Job Satisfaction
- Years at Company
- Work-Life Balance
- Distance From Home

### HR Recommendations

- Improve employee engagement programs
- Reduce overtime pressure
- Strengthen compensation strategies
- Focus on early-career employee retention
- Improve work-life balance initiatives

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---
