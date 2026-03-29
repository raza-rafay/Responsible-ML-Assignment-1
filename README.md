\# Responsible ML Assignment 1 – Translating an R Machine Learning Workflow into Python

\#\# Purpose  
This project reproduces the COMPAS risk score analysis originally implemented in R using Python. The analysis includes data preprocessing, exploratory data analysis (EDA), logistic regression modeling, model evaluation, and fairness analysis across racial groups.

\#\# Libraries Used  
\- pandas  
\- numpy  
\- matplotlib  
\- seaborn  
\- statsmodels  
\- scikit-learn

\#\# Workflow 
1. Load COMPAS dataset
2. Clean and preprocess data
3. Perform exploratory data analysis
4. Build logistic regression model
5. Generate predictions
6. Evaluate model performance
7. Conduct fairness analysis across racial groups

\#\# Key Findings  
The analysis shows disparities in model error rates across racial groups. African-American defendants have a significantly higher false positive rate than Caucasian defendants, meaning they are more likely to be incorrectly labeled high risk. Caucasian defendants show a higher false negative rate, meaning they are more likely to be incorrectly labeled low risk., consistent with the COMPAS study.

\#\# How to Run  
Open the notebook in Google Colab and run all cells to reproduce the analysis.
