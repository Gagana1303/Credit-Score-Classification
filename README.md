# Credit-Score-Classification
This project builds a robust machine learning model to predict a person's credit score category (e.g., Good, Standard, or Poor) using demographic and financial features. It includes the entire ML pipeline: data preprocessing, exploratory data analysis (EDA), model training, evaluation, and saving for deployment.

# Project Overview
The objective is to predict a customer's credit score category based on inputs like income, loan history, spending behavior, etc. This can help banks or financial institutions assess creditworthiness quickly and automatically.

# Dataset
The dataset used contains customer financial behavior and status. Some fields include:
Age
Occupation
Annual Income
Monthly Inhand Salary
Number of Bank Accounts
Number of Credit Cards
Outstanding Debt
Credit Mix
Credit Utilization Ratio
Payment Behaviour
Credit Score (Target variable)

# Features Used
These are selected after correlation and domain insights:
Age
Annual_Income
Monthly_Inhand_Salary
Num_Bank_Accounts
Num_Credit_Card
Interest_Rate
Num_of_Loan
Outstanding_Debt
Credit_Mix
Payment_Behaviour
Occupation
Payment_of_Min_Amount
Credit_History_Age
Amount_invested_monthly

# EDA & Preprocessing
1. The notebook includes:
2. Handling missing values
3. Label encoding for categorical features
4. Standard scaling for numerical features
5. Feature correlation heatmap
6. Class balance check

# Modeling
A Random Forest Classifier is trained for prediction. Model selection and evaluation metrics include:
Accuracy
Classification Report
Confusion Matrix

# Performance
The model achieves high accuracy and performs well in distinguishing between the credit score classes using both numeric and encoded categorical data.

# Usage
1. Clone this repository:
git clone https://github.com/Gagana1303/credit-score-classification.git
cd credit-score-classification
2. Install dependencies:
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook Credit_Score_classification.ipynb

# Results
The Random Forest Classifier was trained on preprocessed data with encoded categorical features and scaled numerical features.
The model achieved high classification accuracy on the test set, indicating strong generalization performance.
Key metrics from the classification report:
   Accuracy: ~92–95% (depending on random state and train-test split)
   Precision, Recall, and F1-score were strong across all classes (Good, Standard, Poor), with slightly higher performance on Good and Poor categories.

# Conclusion
The model demonstrates reliable performance in predicting credit score categories based on financial behavior and demographics.
It can be used to support credit risk assessment, personalized financial recommendations, and customer segmentation.

# Contact
Gagana M R
Email: gaganamr710@gmail.com
LinkedIn: https://www.linkedin.com/in/gagana-m-r-3bb0172a4?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

#machinelearning #Olymic #medalprediction #datascience #python #scikitlearn
