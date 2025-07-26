# Customer Churn Prediction – Telecom Dataset

## Project Overview
This project focuses on predicting customer churn for a telecom company using machine learning. The goal is to identify customers likely to leave (churn) so the company can take proactive measures.

## Dataset
The dataset contains customer data such as demographics, account information, services subscribed, and whether the customer churned or not.

- Source: [Kaggle Telecom Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

## Problem Statement
Predict whether a customer will churn based on their features.

## Approach
- Data loading and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model building: Logistic Regression, Random Forest, XGBoost  
- Model evaluation using accuracy, precision, recall, F1-score, ROC-AUC  
- Interpretation and insights

## Results
The Random Forest and XGBoost models performed best with high accuracy and ROC-AUC scores.

## Usage
1. Download the dataset from Kaggle and place the CSV file (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) in the `data/` folder.  
2. Run the Jupyter notebook `Customer_Churn_Prediction.ipynb`.

## Requirements
- Python 3.x  
- Jupyter Notebook  
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

## References
- Kaggle Dataset: https://www.kaggle.com/blastchar/telco-customer-churn  
- Customer churn prediction tutorials from various sources

