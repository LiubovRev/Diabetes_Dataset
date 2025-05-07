# 🩺 Diabetes Classification using Machine Learning

This project applies machine learning techniques to predict the likelihood of diabetes in patients based on clinical features, using the Pima Indians Diabetes dataset.

## 🚀 Goal

To compare several classification algorithms and evaluate their performance, while also analyzing the importance of features and the effect of data cleaning.

## 🧪 Dataset

- Source: Pima Indians Diabetes dataset (from Kaggle / UCI)
- Features include: Pregnancies, Glucose, BMI, Age, Insulin, etc.

## 📊 Workflow

1. **Data Cleaning & EDA**
   - Removed/imputed zero values for Glucose, BloodPressure, etc.
   - Visualized distributions and class imbalance

2. **Modeling**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost

3. **Evaluation Metrics**
   - Accuracy
   - Precision / Recall
   - AUC-ROC
   - Confusion Matrix

4. **Feature Importance**
   - Used built-in importance in tree-based models

## 🧠 Key Learnings

- XGBoost showed best performance with AUC ≈ 0.84
- Feature engineering & cleaning significantly impacted model accuracy
- Early-stage disease detection benefits from interpretable models

## 📁 File Overview

- `notebooks/diabetes_analysis.ipynb` – Main notebook with full pipeline
- `results/` – Visualizations (feature importance, confusion matrices)
- `requirements.txt` – Libraries used (pandas, sklearn, xgboost, etc.)

## 📌 To Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/diabetes_analysis.ipynb
