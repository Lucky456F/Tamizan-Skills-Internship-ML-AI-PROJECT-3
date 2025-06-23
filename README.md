# Tamizan-Skills-Internship-ML-AI-PROJECT-3

# Loan Eligibility Predictor
A machine learning project to predict loan approval for applicants based on their details. This tool can assist banks, fintech apps, and mock loan assessment platforms in making fast, data-driven decisions.
## 🚩 Problem Statement
Banks want to predict whether an applicant should be granted a loan. Automating this process can improve efficiency and reduce risk.
## 🎯 Objective
- Build a classification model that predicts loan approval based on applicant details such as age, income, education, credit score, etc.
- Use Logistic Regression and Random Forest algorithms.
- Evaluate the model using ROC curve and confusion matrix.
## 🗂️ Dataset
- Contains features like: age, income, education, credit score, employment status, loan amount, etc.
- Target: Loan_Status (Approved/Not Approved)
- Example datasets: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
## 🛠️ Requirements
- Python 3.x
- pandas
- scikit-learn
- matplotlib (for plots)
- seaborn (for plots, optional)
## 🏗️ Project Workflow
1. **Data Collection:** Load the dataset.
2. **Preprocessing:** 
    - Handle missing values
    - Encode categorical features
    - Feature scaling (if needed)
3. **Train/Test Split:** Split data into training and testing sets.
4. **Modeling:** Train Logistic Regression and Random Forest classifiers.
5. **Evaluation:** Use confusion matrix and ROC curve to assess performance.
