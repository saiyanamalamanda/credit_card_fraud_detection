# Credit Card Fraud Detection

## Overview

This project implements a Credit Card Fraud Detection model using machine learning. The dataset consists of credit card transactions, and the goal is to build a model that accurately classifies fraudulent transactions while minimizing false positives.

## Dataset

- The dataset contains transaction details such as amount, merchant details, timestamps, etc.
- The target variable (`Class`) indicates whether a transaction is **fraudulent (1) or legitimate (0).
- Addressed class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**.

## Features Engineering

- Standardized numerical features using **StandardScaler**.
- Created meaningful features such as **transaction frequency, location mismatch, and spending patterns**.

## Technologies Used

- **Python**
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (Preprocessing, Model Evaluation)
- **XGBoost** (Model Training)
- **Matplotlib, Seaborn** (Data Visualization)
- **SMOTE** (Handling Imbalanced Data)
- **Git/GitHub** (Version Control)

## Installation

To run this project, install the required dependencies:

pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib seaborn joblib

## Model Training

1. **Preprocessed the data** (handled missing values, normalized numerical features).
2. **Balanced the dataset** using SMOTE.
3. **Split into training and testing sets**.
4. **Trained XGBoost classifier**.
5. **Evaluated model performance** using accuracy, confusion matrix, and ROC-AUC score.

## Evaluation Metrics

- **Classification Report**
- **Confusion Matrix**
- **ROC-AUC Score**
- **Accuracy**

## Results

The model successfully detects fraudulent transactions while maintaining a low false positive rate. The confusion matrix and ROC-AUC score indicate the model’s performance.

## Usage

Run the Python script:

python creditcardfraud_detection.py


## GitHub Repository

To push this project to GitHub:


git init
git add .
git commit -m "Initial commit - Fraud detection model"
git branch -M main
git remote add origin https://github.com/saiyanamalamanda/credit_card_fraud_detection
git push -u origin main


## License

This project is open-source and free to use.

