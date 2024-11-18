Loan Prediction Mini-Project

Overview
This project focuses on predicting loan eligibility (classification) and loan amounts (regression) using machine learning. It applies various preprocessing, visualization, and modeling techniques to analyze and predict outcomes based on real-world loan datasets.

---

Objectives
1. **Loan Classification**: Predict whether a loan will be approved based on applicant details.
2. **Loan Regression**: Predict the loan amount that will be approved for an applicant.

---

Features
- Data Preprocessing**:
  - Handling missing values
  - Feature scaling
  - Encoding categorical variables
- Data Visualization**:
  - Correlation heatmaps
  - Loan distribution histograms
- Machine Learning Models**:
  - Classification: Logistic Regression, Decision Trees, Random Forest
  - Regression: Linear Regression, Random Forest Regressor
- Model Evaluation**:
  - Classification: Accuracy, Precision, Recall, Confusion Matrix
  - Regression: RMSE, R-Squared

---

Datasets
 1. Loan Classification Dataset
- File: `datasets/loan_classification.csv`
- Description: Dataset for predicting loan approval status (binary classification).
- Features: 
  - Applicant income
  - Loan amount
  - Marital status
  - Education level

2. Loan Regression Dataset
- File: `datasets/loan_regression.csv`
- Description: Dataset for predicting the approved loan amount (regression task).
- Features: 
  - Applicant income
  - Co-applicant income
  - Property area
