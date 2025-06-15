# SECOM Fault Detection Project 🔍

This repository contains the final code and analysis for the SECOM Equipment Fault Detection project, conducted as part of an academic data mining course. The objective was to analyze sensor data from semiconductor manufacturing equipment to identify and classify potential faults using statistical modeling and machine learning techniques.

## 📘 Project Overview

The SECOM dataset includes sensor measurements from a semiconductor fabrication process. The goal is to build a predictive model that can detect faulty equipment behavior, helping to reduce costs and improve yield in high-precision manufacturing.

### 🔧 Main Tasks:

- Exploratory Data Analysis (EDA)
- Feature selection and dimensionality reduction
- Handling missing values
- Building classification models
- Model evaluation and optimization using grid search


> ⚠️ **Note**: Due to licensing restrictions, the SECOM dataset is not included in this repository. You can download it from the UCI Machine Learning Repository:  
> [SECOM Dataset on UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/SECOM)

## 📊 Techniques Used

- **Data Preprocessing**:
  - Replacing missing values with statistical imputation
  - Normalizing and standardizing features
  - Removing constant/near-zero variance features

- **Feature Engineering**:
  - Principal Component Analysis (PCA)
  - Recursive Feature Elimination (RFE)

- **Modeling**:
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - Hyperparameter tuning via GridSearchCV

- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC

## 🧠 Key Insights

- Many sensors are redundant or inactive; dimensionality reduction is crucial.
- Class imbalance poses challenges; handled via balanced metrics and model tuning.
- Random Forest performed best in terms of generalization and interpretability.

## 🛠 Technologies

- **Languages**: Python  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
