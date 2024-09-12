# -Credit-Risk-Analysis-
 Credit Risk Analysis Report
Overview
This analysis evaluates the credit risk of borrowers by predicting whether a loan will be healthy or at high risk of default based on a set of financial features. We used a logistic regression model to perform this classification.

Results
Accuracy Score: 99%
Precision Score:
Healthy Loans (0): 1.00
High-Risk Loans (1): 0.86
Recall Score:
Healthy Loans (0): 0.99
High-Risk Loans (1): 0.94
Summary
The logistic regression model performed exceptionally well in predicting both healthy loans (0) and high-risk loans (1). The model achieved an accuracy of 99%, demonstrating its overall effectiveness. Precision and recall scores indicate that the model is highly reliable for predicting healthy loans, with perfect precision and high recall. For high-risk loans, the model maintains a good balance between precision and recall, although precision is slightly lower compared to healthy loans.

Given these results, the logistic regression model is recommended for use in predicting creditworthiness. The high accuracy and balanced performance across both classes make it a robust tool for identifying both healthy and high-risk loans. This will aid in effective credit risk management and decision-making.

Next Steps
Model Refinement: Consider experimenting with other algorithms or tuning hyperparameters to further improve precision for high-risk loans.
Feature Engineering: Explore additional features or transformations to enhance model performance.
Deployment: Integrate the model into a credit risk management system for real-time predictions.
