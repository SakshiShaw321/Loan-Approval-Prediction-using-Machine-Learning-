---

# 🏦 Loan Approval Prediction Using Machine Learning

### 📘 Overview

This project predicts **loan approval status** based on customer financial and demographic data using multiple machine learning models.
It analyzes factors such as income, CIBIL score, education, and asset values to determine loan eligibility.

---

### 📂 Dataset

**File:** `loan_approval_dataset.csv`
**Shape:** 4,269 rows × 13 columns

**Features:**

| Column                     | Description                                           |
| -------------------------- | ----------------------------------------------------- |
| `loan_id`                  | Unique loan ID                                        |
| `no_of_dependents`         | Number of dependents                                  |
| `education`                | Applicant’s education level (Graduate / Not Graduate) |
| `self_employed`            | Employment type (Yes / No)                            |
| `income_annum`             | Annual income                                         |
| `loan_amount`              | Requested loan amount                                 |
| `loan_term`                | Duration of loan in months                            |
| `cibil_score`              | Applicant’s credit score                              |
| `residential_assets_value` | Value of residential assets                           |
| `commercial_assets_value`  | Value of commercial assets                            |
| `luxury_assets_value`      | Value of luxury assets                                |
| `bank_asset_value`         | Bank holdings value                                   |
| `loan_status`              | Target variable: Approved / Rejected                  |

---
### 🧠 Models Used
The notebook (code.ipynb) implements and compares multiple algorithms:
Logistic Regression	
Support Vector Machine	
Decision Tree
Random Forest	
Naive Bayes	
K-Nearest Neighbors        

---

### 🔍 Exploratory Data Analysis (EDA)

* Verified data integrity (no missing values)
* Checked class distribution for `loan_status`
* Compared **CIBIL scores** for approved vs rejected loans
* Visualized relationships between income, loan amount, and approval

---

### ⚙️ Machine Learning Workflow

1. **Data Cleaning & Preprocessing**

   * Stripped whitespace in column names
   * Encoded categorical variables
   * Split data into train (80%) and test (20%) sets

2. **Model Training & Evaluation**

   * Trained multiple classification models
   * Computed Accuracy, Precision, Recall
   * Visualized feature importance

---

### 📊 Key Insights

* Higher **CIBIL score** and **annual income** significantly increase loan approval likelihood.
* **Random Forest** and **Decision Tree** models deliver the highest accuracy.
* Logistic Regression provides interpretable results with solid baseline performance.
* Loan rejections are concentrated in low CIBIL score ranges (300–700).

---

### 🧰 Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy
* **IDE:** Jupyter Notebook




