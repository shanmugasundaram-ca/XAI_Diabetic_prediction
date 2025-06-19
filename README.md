# 🧠 Explainable AI for Diabetes Prediction Using SHAP

This project applies **Explainable AI (XAI)** techniques using **SHAP (SHapley Additive exPlanations)** to interpret machine learning models trained on the PIMA Indian Diabetes dataset.

It demonstrates how different ML models explain predictions and how insights can be extracted both globally and at an individual level (patient-wise).

---

## 📌 Features

- 🔍 Predicts diabetes outcome using 3 machine learning models:
  - Logistic Regression
  - XGBoost Classifier
  - Gradient Boosting Classifier (from Scikit-learn)
  
- 📊 Evaluates performance using:
  - Accuracy
  - Sensitivity (Recall)
  - Specificity

- 📉 Visualizes SHAP explanations:
  - Waterfall plot
  - Force plot
  - Bar plot
  - Beeswarm plot

- 👤 Supports custom patient input for real-time SHAP interpretation.

---

## 📁 Dataset

- **PIMA Indian Diabetes Dataset**
- Source: [`diabetes.csv`](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## ⚙️ Requirements

Install the following Python libraries:

```bash
pip install pandas scikit-learn shap xgboost matplotlib
