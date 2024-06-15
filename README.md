# Loan Eligibility Prediction

## Overview
Dream Housing Finance company aims to automate the loan eligibility process based on customer details provided during the online application process. The objective is to identify customer segments eligible for loan amounts to target these customers specifically.

## Problem Statement
The company wants to automate the loan eligibility process (real-time) based on customer details provided while filling out the online application form. These details include:
- Gender
- Marital Status
- Education
- Number of Dependents
- Income
- Loan Amount
- Credit History
- And others

The goal is to predict loan eligibility based on the provided dataset.

## Data Description
The dataset includes the following fields:
- **Loan_ID**: Unique Loan ID
- **Gender**: Male/Female
- **Married**: Applicant married (Y/N)
- **Dependents**: Number of dependents
- **Education**: Applicant Education (Graduate/Undergraduate)
- **Self_Employed**: Self-employed (Y/N)
- **ApplicantIncome**: Applicant income
- **CoapplicantIncome**: Coapplicant income
- **LoanAmount**: Loan amount in thousands
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history meets guidelines (1/0)
- **Property_Area**: Urban/Semi-Urban/Rural
- **Loan_Status**: Loan approved (Y/N)

## Approach
1. **Data Preprocessing**: Handle missing values, encode categorical variables, and normalize numerical features, encoding cateforical variables.
2. **Exploratory Data Analysis (EDA)**: Understand the distribution of variables and relationships between them, univariate and bivariate analysis, correlational analysis.
3. **Model Building**: Use machine learning algorithms to build predictive models, Logistic Regression, Random Forest, Gradient Boosting, SVM, KNN, Decision Trees, Naive Bayes, Ensemble Methods- Bagging and Stacking
4. **Model Evaluation**: Evaluate models using appropriate metrics and select the best-performing model.

## Author
- Niharika J N
- niharika.jkn07@gmail.com
- https://www.linkedin.com/in/niharika-jkn/
