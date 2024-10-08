# credit-risk-classification
Credit Risk Classification Project
Overview
This project aims to classify loans as either "healthy" or "high-risk" using machine learning models. By leveraging logistic regression, the goal is to predict the likelihood of a loan being high-risk based on various financial features. The results are evaluated using common classification metrics, such as accuracy, precision, recall, and F1-score.

Files in the Repository
credit_risk_classification.ipynb: The main Jupyter notebook where the code for data loading, preprocessing, model training, and evaluation is implemented.
credit_risk_classification-checkpoint.ipynb: A checkpoint of the notebook saved during the development process.
lending_data.csv: The dataset containing the lending information used for training and testing the model.
report-template.md: A markdown template that may be used for generating reports related to the project.
Dataset Description
The lending_data.csv file contains the following columns:

loan_size: The size of the loan.
interest_rate: The interest rate of the loan.
borrower_income: The income of the borrower.
debt_to_income: The borrower's debt-to-income ratio.
num_of_accounts: The number of credit accounts the borrower has.
derogatory_marks: The number of derogatory marks on the borrower’s credit report.
total_debt: The total debt of the borrower.
loan_status: The target variable, where 0 represents a healthy loan and 1 represents a high-risk loan.
Project Workflow
Data Preprocessing:

Load the dataset and handle any missing or irrelevant data.
Split the data into features and target variables.
Scale the feature variables for optimal performance in the machine learning models.
Model Training:

Train a logistic regression model to classify loans into healthy or high-risk categories.
Evaluate the performance using metrics such as precision, recall, accuracy, and F1-score.
Model Evaluation:

Analyze the model's performance based on the classification report.
Assess how well the model performs in predicting both healthy loans and high-risk loans.
Results Analysis:

Examine how well the model predicts the different classes by looking at precision, recall, and F1-score for each class.
Key Results
Model Performance: The logistic regression model achieves high accuracy (99%) and performs well in predicting healthy loans (precision, recall, and F1-score of 1.00). However, the model shows slightly lower performance in predicting high-risk loans, with an F1-score of 0.88.

Conclusion
This project demonstrates the application of logistic regression to classify loan risks based on borrower financial features. While the model performs exceptionally well for predicting healthy loans, it shows slightly reduced performance in identifying high-risk loans, suggesting that additional feature engineering or model tuning may improve results.