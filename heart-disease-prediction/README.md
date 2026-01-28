# Heart Disease Prediction using Machine Learning

## Project Overview
This repository contains an end-to-end machine learning project that predicts the
presence of heart disease based on clinical and demographic features. The pipeline
includes data exploration, preprocessing, model training, evaluation, and interpretation.

## 📍 Dataset
The dataset used in this project is based on the UCI Heart Disease dataset, containing
multiple patient records with health measurements and a binary target indicating the
presence (`1`) or absence (`0`) of heart disease. This project uses `heart.csv` located
in the `data/` folder.

## 🔍 Notebook
- `heart_disease_prediction.ipynb`  
  Contains the complete machine learning workflow:
  - Data understanding and distribution plots
  - Feature engineering & preprocessing
  - Model training (Logistic Regression, Random Forest)
  - Cross-validation
  - Feature importance interpretation

## 🧾 Data Dictionary
Refer to `data_dictionary.csv` for feature descriptions.

## 📊 Results Summary
- Logistic Regression Accuracy: ~79.5%
- Random Forest Accuracy: ~98.5%
- Cross-validated performance confirms model stability
- Feature Importance highlights key predictors such as age, chest pain type, and max heart rate

## 🛠️ Tools & Libraries
- Python (3.x)
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

## ⚙️ Setup / Installation
To run this project locally:

```bash
git clone https://github.com/<your_username>/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt
