# Loan-Approval-Prediction-using-Machine-Learning-
🏦 Loan Approval Prediction using Machine Learning
📘 Project Overview

This project predicts loan approval status based on applicant details such as income, loan amount, CIBIL score, employment status, and other financial indicators.
It applies multiple machine learning models and compares their performance to identify the best one.

📂 Dataset

File: loan_approval_dataset.csv

Shape: 4,269 rows × 13 columns


| Column                     | Description                                 |
| -------------------------- | ------------------------------------------- |
| `loan_id`                  | Unique ID for each loan application         |
| `no_of_dependents`         | Number of dependents of the applicant       |
| `education`                | Education level (Graduate / Not Graduate)   |
| `self_employed`            | Employment type (Yes / No)                  |
| `income_annum`             | Annual income of the applicant              |
| `loan_amount`              | Loan amount requested                       |
| `loan_term`                | Loan term (in months)                       |
| `cibil_score`              | CIBIL credit score                          |
| `residential_assets_value` | Value of residential property               |
| `commercial_assets_value`  | Value of commercial property                |
| `luxury_assets_value`      | Value of luxury assets (e.g., car, jewelry) |
| `bank_asset_value`         | Value of bank holdings                      |
| `loan_status`              | Target variable (Approved / Rejected)       |


🧠 Models Implemented
The following classification algorithms were used and compared:
Logistic Regression	

Support Vector Machine	

Decision Tree	

Random Forest

Naive Bayes

K-Nearest Neighbor

🔍Exploratory Data Analysis (EDA)

Checked for missing values and data types

Visualized distribution of loan approvals

Compared CIBIL scores for approved vs. rejected applicants

Examined income and asset value patterns

Applied t-tests to check significance of CIBIL differences

⚙️ Machine Learning Workflow

Data Cleaning & Preprocessing

Stripped whitespace in column names

Encoded categorical variables

Split data into train (80%) and test (20%) sets

Model Training & Evaluation

Trained multiple classification models

Computed Accuracy, Precision, Recall

Visualized feature importance

Key Insights
Higher CIBIL score and annual income significantly increase loan approval likelihood.

Random Forest and Decision Tree models deliver the highest accuracy.

Logistic Regression provides interpretable results with solid baseline performance.

Loan rejections are concentrated in low CIBIL score ranges (300–700).

🧰 Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy

IDE: Jupyter Notebook
