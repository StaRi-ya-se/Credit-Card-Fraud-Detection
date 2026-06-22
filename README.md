Credit Card Fraud Detection using Ensemble Learning
Project Overview

This project addresses the challenge of detecting fraudulent credit card transactions in a highly imbalanced dataset. Multiple machine learning models were trained and combined using ensemble learning techniques to improve fraud detection performance.

Features
Data preprocessing and cleaning
Handling class imbalance using SMOTE
Logistic Regression
Random Forest
XGBoost
Soft Voting Ensemble
Probability Calibration
Threshold Optimization
SHAP Explainability
Dataset

Dataset used:

Credit Card Fraud Detection Dataset

The dataset contains anonymized transaction features and a binary target variable indicating fraudulent and legitimate transactions.

Tech Stack
Python
Pandas
NumPy
Scikit-learn
XGBoost
Imbalanced-learn
SHAP
Matplotlib
Seaborn
Model Performance
Metric	Score
PR-AUC	0.8629
ROC-AUC	0.9557
Visualizations
Class Distribution

Confusion Matrix

SHAP Feature Importance

Repository Structure
credit-card-fraud-detection/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── LICENSE
Future Improvements
Hyperparameter optimization
Deep learning approaches
Real-time fraud detection pipeline
Model deployment using FastAPI