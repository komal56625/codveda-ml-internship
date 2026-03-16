# Task 3 - Logistic Regression

## Description
Logistic Regression model to predict customer churn.

## Steps Performed
- Loaded and merged Churn dataset (3333 rows)
- Dropped unnecessary columns (Area code, Charge columns)
- Encoded categorical variables
- Standardized numerical features
- Trained Logistic Regression with class_weight='balanced'
- Evaluated using Accuracy, Precision, Recall
- Plotted Confusion Matrix and ROC Curve

## Results
- Accuracy  : 0.78
- Precision : 0.38
- Recall    : 0.79
- AUC Score : 0.84

## Dataset
- churn-bigml-80.csv
- churn-bigml-20.csv

## Tools Used
- Python, Pandas, Scikit-learn, Matplotlib
