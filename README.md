# Loan Approval Prediction Model

This repository contains code for a machine learning model that predicts loan approval status based on various applicant details. The model was trained on a small dataset consisting of 600 loan applications. The dataset includes the following features:

```
df.columns
```
['Loan_ID', 'Gender', 'Married', 'Dependents', 'Education',
       'Self_Employed', 'ApplicantIncome', 'CoapplicantIncome', 'LoanAmount',
       'Loan_Amount_Term', 'Credit_History', 'Property_Area', 'Loan_Status']

The machine learning model in this repository uses the Python programming language and the scikit-learn library. The model was trained using the Support Vector Machine (SVM) algorithm with the 'linear' kernel. The model achieved a training accuracy of 79% and a test accuracy of 81%.

The repository includes code for Exploratory Data Analysis (EDA), data preprocessing, and model training. The EDA code includes data visualization techniques to help understand the relationships between the features and the target variable. The data preprocessing code includes data cleaning, handling missing values, and converting categorical variables to numerical ones.

## Requirements

Python 3.7

scikit-learn library
