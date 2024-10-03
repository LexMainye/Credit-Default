# Credit Payment Default Prediction Using Machine Learning
# Project Overview
This project aims to predict credit payment defaults using machine learning techniques based solely on payment data. By analyzing historical payment patterns, we aim to identify customers at risk of defaulting on their loans or credit payments, helping financial institutions make informed decisions and mitigate risk.

# Objective
The main objective is to build a predictive model that can classify whether a customer will default on a payment in the upcoming period. The dataset used contains detailed information about past payment behaviors, including the amount paid, payment dates, and any late payments.

# Link to the Dataset used : https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
Libraries used : pandas,numpy,seaborn,sklearn,

 # Dataset Description
The dataset includes the following features :
1. Customer ID: Unique identifier for each customer
2. Age
3. Sex
4. Marital status
5. Education level
6. Payment status:represented by PAY_0 to PAY_6
7. Bill Statement: represented by BILL_AMT1 TO BILL_AMT6
8. Previous Payment:represented by PAY_AMT1 to PAY_AMT6
9. Default payment next month.

# Steps and Methodology #

# Data Preprocessing
- Handling missing or incomplete payment data.
- Normalizing and scaling payment amounts for consistent model input.
- Creating new features like the number of days late for each payment or payment consistency over time.

# Exploratory Data Analysis (EDA)

- Visualizing key payment patterns to understand the characteristics of male and female creditors .
- Correlation analysis between payment features and the default outcome.
- Introducing statistical features (mean, median, variance) of payment patterns.

# Model Building
Used classification algorithms such as Random Forest where the  decision tree used predicts whether a loan will default or not.


# Results:
The best-performing model showed an with an AUC of 0.75, showing the model has moderate predictive power.

