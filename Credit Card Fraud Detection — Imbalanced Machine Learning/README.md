# 💳 Credit Card Fraud Detection using Machine Learning

## 🚀 Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques on a highly imbalanced financial dataset.

The objective is to identify fraudulent transactions while minimizing false positives and improving recall, which is critical in real-world fraud detection systems.

---

## 🎯 Objective

To build a robust fraud detection pipeline capable of identifying rare fraudulent transactions using advanced machine learning models and imbalance handling techniques.

---

## 📊 Dataset

Dataset used:

* Credit Card Fraud Detection Dataset
* Source: Kaggle

Dataset characteristics:

* 284,807 transactions
* 492 fraud cases
* Highly imbalanced dataset
* Features: V1–V28 (PCA transformed), Time, Amount
* Target Variable: Class (0 = Normal, 1 = Fraud)

---

## 🧠 Machine Learning Approach

### 🔹 Data Preprocessing

* Missing value handling
* Feature scaling
* Train-test split
* Class imbalance analysis

---

### 🔹 Imbalance Handling

Since fraud cases are extremely rare, standard accuracy is unreliable.

Techniques used:

* SMOTE (Synthetic Minority Oversampling Technique)
* Class Weight Balancing
* Threshold Tuning

---

### 🔹 Models Used

* Logistic Regression
* Random Forest Classifier
* Balanced Random Forest
* XGBoost (Advanced version)

---

### 🔹 Evaluation Metrics

* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Threshold Optimization

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn
* XGBoost
* Matplotlib
* Seaborn

---

## 📈 Results

### Model Performance

* Logistic Regression Accuracy: 78.6%
* Random Forest Accuracy: 80.1%
* Balanced Random Forest Accuracy: 80.3%

### Threshold Tuning

Improved fraud detection by optimizing prediction threshold for better recall and business usability.

---

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Run Notebook

```bash
jupyter notebook
```

---

## 💡 Key Learnings

* Working with highly imbalanced datasets
* Fraud detection strategy design
* Threshold tuning for business applications
* Precision vs Recall tradeoff
* Model optimization for financial systems

---

## 🔮 Future Improvements

* Deep learning models
* Autoencoder-based anomaly detection
* Real-time fraud detection API
* Streamlit deployment for live prediction

---

## 👤 Author

**Tushar Dobal**
Aspiring Data Scientist | Machine Learning Enthusiast

---

## 💼 Portfolio Value

This project demonstrates:

* End-to-end ML pipeline
* Imbalanced classification
* Financial fraud analytics
* Model optimization
* Real-world business problem solving

---
