🏦 Bank Customer Churn Prediction
This project predicts whether a bank customer will churn (leave the bank) using a machine learning pipeline that includes SMOTE for handling class imbalance and a Neural Network (NN) for prediction. The goal is to help banks identify and retain at-risk customers.

📊 Dataset Overview
Rows: 10,000 customers
Columns: 12 features including customer demographics, account info, and churn status
Target Variable: churn (1 = customer will leave, 0 = customer stays)

Feature Columns:
| Feature Name      | Description                                |
| ----------------- | ------------------------------------------ |
| customer\_id      | Unique customer ID                         |
| credit\_score     | Customer's credit score                    |
| country           | Country of residence (e.g., France, Spain) |
| gender            | Gender of the customer                     |
| age               | Age in years                               |
| tenure            | Number of years as a customer              |
| balance           | Account balance                            |
| products\_number  | Number of bank products used               |
| credit\_card      | Has credit card (1 = Yes, 0 = No)          |
| active\_member    | Actively uses services (1 = Yes, 0 = No)   |
| estimated\_salary | Estimated annual salary                    |
| churn             | Target label (1 = Churn, 0 = Not churn)    |
