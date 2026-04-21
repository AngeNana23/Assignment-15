# Assignment-15

# Objective
Build a machine learning model to predict loan default risk using borrower data.

# Dataset
File: bank-loan.csv
Target variable: default (1 = default, 0 = no default)

# Tools Used
Python
Pandas
Scikit-learn
Matplotlib
Seaborn
SHAP

# Steps
Loaded and explored dataset
Cleaned missing values
Created new features based on debt and income
Trained Random Forest model
Evaluated model performance
Used SHAP for explainability
Performed fairness analysis using age groups

# Results
Model achieved good accuracy
Debt-related features were most important
SHAP improved interpretability of predictions

# How to Run
Upload bank-loan.csv
Run the notebook in Jupyter or Google Colab
Install dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn shap

# Ethics
Checked fairness across age groups
Used SHAP for transparency
Avoided sensitive data misuse
