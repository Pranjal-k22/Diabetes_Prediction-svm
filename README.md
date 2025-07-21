# 🩺 Diabetes Prediction System using SVM

A machine learning-based diagnostic tool to predict whether a person is diabetic or not, using the PIMA Indian Diabetes dataset and a Support Vector Machine (SVM) classifier. This project is built using Python and Scikit-learn and can serve as a solid foundation for more advanced healthcare analytics systems.

---

## 📌 Table of Contents

- [Demo](#demo)
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)

---

## 🧠 Overview

This project is a binary classification task to predict diabetes in patients using physiological data. The SVM algorithm is used due to its effectiveness in handling high-dimensional data and binary classification problems.

---

## 📊 Dataset
- **Format**: CSV
- **Samples**: 768
- **Features**: 8 input features and 1 output label (`Outcome`)

### Feature Columns

| Feature                  | Description                                  |
|--------------------------|----------------------------------------------|
| Pregnancies              | Number of pregnancies                        |
| Glucose                  | Plasma glucose concentration                 |
| BloodPressure            | Diastolic blood pressure (mm Hg)             |
| SkinThickness            | Triceps skin fold thickness (mm)             |
| Insulin                  | 2-Hour serum insulin (mu U/ml)               |
| BMI                      | Body mass index (weight in kg/(height)^2)    |
| DiabetesPedigreeFunction | Diabetes pedigree function                   |
| Age                      | Age (years)                                  |
| Outcome                  | 0 = Non-diabetic, 1 = Diabetic               |

---

## ✨ Features

- Clean and modular Python code.
- Feature scaling using `StandardScaler`.
- SVM classifier using a linear kernel.
- Model accuracy evaluation on both training and test data.
- User input support for real-time prediction.

---
