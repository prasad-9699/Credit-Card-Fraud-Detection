# Credit Card Fraud Detection using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prasad-9699/Credit-Card-Fraud-Detection/blob/main/Credit_Card_Fraud_Detection.ipynb)

## 📊 Project Overview

An end-to-end machine learning project to detect fraudulent credit card transactions using ensemble methods (Random Forest and XGBoost). Successfully handled a highly imbalanced dataset and achieved **~94% accuracy** and **90% F1-score**.

### 🎯 Key Results
- **Accuracy:** ~94%
- **F1-Score:** ~90%
- **ROC-AUC:** ~0.97
- Successfully handled **highly imbalanced dataset** (0.172% fraud rate)

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas & NumPy** - Data manipulation
- **Scikit-learn** - Machine learning algorithms
- **XGBoost** - Gradient boosting
- **imbalanced-learn (SMOTE)** - Handling class imbalance
- **Matplotlib & Seaborn** - Data visualization

## 📁 Dataset

- **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Fraud cases:** 492 (0.172%)
- **Features:** 30 (Time, Amount, V1-V28 PCA components)

## 🔬 Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed class distribution
- Visualized transaction patterns
- Feature correlation analysis

### 2. Data Preprocessing
- Feature scaling using StandardScaler
- Train-test split (80-20)
- Handled missing values

### 3. Dimensionality Reduction
- PCA visualization for 2D representation

### 4. Handling Class Imbalance
- Applied SMOTE (Synthetic Minority Over-sampling Technique)
- Balanced training data from 1:577 to 1:1 ratio

### 5. Model Training
- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter optimization

### 6. Model Evaluation
- Confusion Matrix
- ROC-AUC Curve
- Precision-Recall Curve
- Classification Report
- Feature Importance Analysis

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Click the "Open in Colab" badge above
2. Run all cells in sequence
3. Upload your dataset when prompted

### Option 2: Local Setup
