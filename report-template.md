# Module 12 Report Template

# Overview of the Analysis
In this analysis, we aimed to build and evaluate a machine learning model to predict the creditworthiness of borrowers based on their financial data. The primary goal was to identify whether a loan would be healthy (low risk) or high-risk (potential default) using historical financial information.

# Purpose of the Analysis
The purpose of this analysis was to develop a predictive model that can classify loans into two categories:

Healthy (0): Loans that are not expected to default.
High-risk (1): Loans with a high risk of default.
Financial Information and Prediction Target
The dataset included various financial features such as income, loan amount, and credit score, along with the target variable, loan_status, which indicates whether a loan is healthy or high-risk. We aimed to predict the value of loan_status based on the features.

# Variables
Target Variable: loan_status
Value Counts:
0 (Healthy Loan): [Number of healthy loans]
1 (High-Risk Loan): [Number of high-risk loans]
# Machine Learning Process

Data Preparation: Loaded the dataset and split it into features (X) and target variable (y). Preprocessed the data to handle missing values and categorical variables as needed.
Train-Test Split: Divided the dataset into training and testing sets to evaluate model performance on unseen data.
Model Selection: Used Logistic Regression to build the classification model.
Model Training: Trained the logistic regression model on the training dataset.
Model Evaluation: Assessed model performance using metrics like accuracy, precision, recall, and the ROC curve.
# Methods Used
Logistic Regression: A classification algorithm used to predict the probability of a binary outcome. It was chosen for its interpretability and effectiveness in binary classification tasks.
# Results
Machine Learning Model 1: Logistic Regression
Accuracy: 99%
Precision (for class 0): 1.00
Recall (for class 0): 0.99
Precision (for class 1): 0.86
Recall (for class 1): 0.94
# Summary
The logistic regression model performed exceptionally well overall:

# Best Performance: The model achieved a high accuracy of 99%, indicating excellent overall performance.
# Precision and Recall: The model showed perfect precision and high recall for predicting healthy loans (class 0) and good precision and recall for high-risk loans (class 1). 
Although precision for high-risk loans was lower than for healthy loans, the recall was quite high, suggesting that the model is effective at identifying most high-risk loans.

# Recommendation
Best Model: The logistic regression model is recommended due to its high accuracy and balanced performance across both classes.
Performance Considerations: In this context, predicting high-risk loans (class 1) is crucial for minimizing financial risk. The model's high recall for class 1 ensures that most potential defaults are identified, which is valuable for managing credit risk.
Overall, the logistic regression model provides a reliable and effective tool for predicting loan creditworthiness and should be used for ongoing risk assessment and management.