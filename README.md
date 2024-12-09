# Loan Prediction Model with Row-Wise Pattern Analysis
## Project Overview

This project implements a loan prediction system using a dataset of loan applications. The model leverages:

## Data Preprocessing:
- Encoding categorical variables.
- Scaling numerical features.
- Filling missing values.
- Row-Wise Pattern Recognition:
- Extracting and analyzing patterns in individual columns.
## Machine Learning:
- A Random Forest classifier predicts loan approval (Loan_Status).
## Dataset
- The dataset contains features such as applicant income, loan amount, education, marital status, and loan status. It includes the following columns:

Categorical Columns:
  Gender, Married, Education, Self_Employed, Property_Area, Loan_Status.
Numerical Columns:
  ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History.
Target Variable:
  Loan_Status (1 for approved, 0 for denied).

## Setup Instructions
Install Dependencies:
  pip install pandas numpy scikit-learn matplotlib
Prepare the Dataset:
  Place the dataset (train.csv) in the project directory.
  Ensure it matches the expected structure.
  Run the Script: Execute the Python script provided below.
## How It Works
### Data Preprocessing:
- Fills missing loan amounts with the median value.
- Encodes categorical columns into numeric labels using LabelEncoder.
-Scales numeric columns for consistent model input using StandardScaler.
### Pattern Recognition:
-Analyzes row-wise patterns in individual columns using subsequence identification.
### Prediction:
- Trains a Random Forest classifier using preprocessed features.
- Predicts Loan_Status for unseen test data.
### Evaluation:
- Outputs:
  Classification Report: Precision, recall, F1-score.
  Confusion Matrix: True positives, false positives, etc.
  Accuracy Score: Overall model accuracy.
