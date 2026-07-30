# 🏦 Loan Approval Prediction Project

## 📖 Overview
This repository contains a machine learning pipeline designed to analyze applicant financial profiles and predict whether a loan application will be approved or denied.

The dataset contains **1,000 records** across **20 distinct features** covering applicant demographics, financial standings, credit scores, and requested loan parameters.

---

## 📊 Dataset Overview

* **Total Samples:** 1,000 entries
* **Total Features:** 20 features (12 numerical, 8 categorical)
* **Target Variable:** `Loan_Approved` (`Yes` / `No`)

### Key Features
* **Financial Profile:** `Applicant_Income`, `Coapplicant_Income`, `Savings`, `DTI_Ratio`, `Credit_Score`, `Existing_Loans`
* **Loan Request Details:** `Loan_Amount`, `Loan_Term`, `Loan_Purpose`, `Collateral_Value`
* **Demographics:** `Age`, `Gender`, `Marital_Status`, `Dependents`, `Education_Level`
* **Employment & Location:** `Employment_Status`, `Employer_Category`, `Property_Area`

---

## 🛠️ Data Preprocessing & Pipeline Highlights
* **Missing Value Imputation:** Handled missing data across numerical (median/mean) and categorical (mode) features.
* **Feature Engineering & Cleaning:** Stripped non-informative identifiers like `Applicant_ID`.
* **Categorical Encoding:** Converted non-numeric categories via One-Hot / Ordinal Encoding for model training.

---

## 🚀 Tech Stack
* **Language:** Python
* **Data Processing & Analysis:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`
* **Machine Learning:** `scikit-learn`
