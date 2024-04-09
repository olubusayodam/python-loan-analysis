# Loan Prediction Analysis Using Python
This project aims to predict loan approval status based on various features using Python programming language. It involves exploratory data analysis (EDA), data preprocessing, machine learning, model building, and evaluation.
## Overview
The dataset consists of 614 entries and 13 columns.
Features include both numerical and categorical variables.
Notable features: Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, and Loan_Status

The loan prediction analysis project involves the following steps:

1. Data loading and exploration to understand the dataset's structure and contents.
2. Data preprocessing, including handling missing values, encoding categorical variables, and scaling numerical features.
3. Exploratory data analysis (EDA) to gain insights into the dataset and understand the relationships between different features.
4. Building machine learning models for loan prediction using algorithms such as logistic regression, support vector machine (SVM), or decision trees.
5. Evaluating model performance using appropriate metrics and techniques.
The dataset used in this project contains information about loan applicants, including attributes such as gender, marital status, education, income, loan amount, loan term, credit history, and property area. It consists of both numerical and categorical features
## Project Structure

The repository contains the following files:

- `loanpredictionanalysis.ipynb`: Jupyter Notebook containing the Python code for data analysis, preprocessing, and model building.
- `loan_dataset.xls`: Dataset file containing the loan data used for analysis and modeling.

## Identified Issues:

Non-normalized distribution of numerical features.
Missing values in multiple columns.

## Data Cleaning
### Missing Values:
Missing values handled by imputing mode for categorical features and mean for numerical features.
Columns with missing values: Gender, Married, Dependents, Self_Employed, LoanAmount, Loan_Amount_Term, and Credit_History.

## Data Preprocessing and Transformation:
### Categorical Encoding:Categorical variables encoded using one-hot encoding to convert them into numerical representations.

## Conclusion:
This analysis provides valuable insights into the loan dataset, addressing issues such as missing values and data distribution. The trained logistic regression model demonstrates promising performance in predicting loan approval status. Further exploration and refinement may enhance model accuracy and contribute to more informed decision-making in lending institutions.
