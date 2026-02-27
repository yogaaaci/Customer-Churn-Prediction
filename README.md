[README.md](https://github.com/user-attachments/files/25599035/README.md)
# 📊 Customer Churn Prediction

## 📌 Project Overview

This project analyzes customer churn behavior and builds a predictive
model to identify customers who are most likely to leave the service.

The analysis combines: - Exploratory Data Analysis (EDA) - Feature
engineering - Logistic Regression modeling - Model evaluation (Confusion
Matrix, Classification Report, ROC-AUC)

The goal of this project is to understand churn drivers and quantify the
potential business impact.

------------------------------------------------------------------------

## 🎯 Business Objectives

This project aims to answer the following key business questions:

1.  Who are the customers most likely to churn?
2.  Why are they churning?
3.  What is the potential revenue loss?

------------------------------------------------------------------------

## 📂 Dataset

The dataset source of this project is from kaggle

Kaggle Dataset : [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

------------------------------------------------------------------------

## 🔎 Exploratory Data Analysis (EDA)

Key findings from the analysis:

-   Customers with **Month-to-Month contracts** have significantly
    higher churn rates.
-   Customers with **short tenure** are more likely to churn.
-   Higher **monthly charges** are associated with increased churn
    probability.
-   Long-term contract customers (1-year and 2-year) show very low churn
    rates.

These findings indicate that contract type, tenure, and pricing
structure strongly influence churn behavior.

------------------------------------------------------------------------

## 🤖 Modeling Approach

### Logistic Regression

-   Feature scaling applied before training\
-   Used as the primary predictive model\
-   Evaluated using classification metrics and ROC-AUC

The model successfully identifies high-risk churn customers and provides
interpretable results.

------------------------------------------------------------------------

## 🛠️ Tech Stack

Python: 3.12.12 
Pandas: 2.3.3
NumPy: 2.0.2
Matplotlib: 3.10.0
Seaborn: 0.13.2
Scikit-learn: 1.6.1

