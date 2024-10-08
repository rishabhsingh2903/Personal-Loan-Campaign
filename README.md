AIML Personal Loan Campaign Project
Project Overview
This project aims to help AllLife Bank identify liability customers (depositors) with a high probability of accepting a personal loan offer. By leveraging machine learning, the project analyzes customer attributes to enhance marketing strategies for loan offers and improve customer targeting.

Problem Statement
AllLife Bank has a predominantly depositor-based customer base, and it aims to convert these customers into loan customers. The bank’s previous campaign successfully converted over 9% of liability customers to loan customers. This project’s goal is to build a predictive model to assist the marketing team in targeting potential loan customers effectively.

Objectives
Predict whether a customer will accept a personal loan offer based on various customer attributes.
Identify significant attributes that influence a customer’s decision to accept a loan.
Enable the marketing team to target high-probability customers and optimize campaign resources.
Data Dictionary
The dataset includes the following key attributes:

ID: Customer ID
Age: Customer’s age
Experience: Years of professional experience
Income: Annual income (in thousands)
ZIP Code: Customer’s ZIP code
Family: Family size of the customer
CCAvg: Average credit card spending per month (in thousands)
Education: Education level (1 = Undergrad, 2 = Graduate, 3 = Advanced/Professional)
Mortgage: Mortgage value (in thousands)
Personal_Loan: Indicator of personal loan acceptance in the last campaign
Securities_Account, CD_Account, Online, CreditCard: Other banking services used by the customer
Methodology
Data Loading: Imported necessary libraries and loaded the dataset for analysis.
Exploratory Data Analysis (EDA): Performed to understand data distribution and identify patterns or correlations.
Model Building: Developed a machine learning model using a decision tree classifier to predict the likelihood of a customer accepting a loan.
Evaluation: Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.
Insights & Recommendations
Based on the model's findings:

High-income customers with substantial credit card spending were more likely to accept loan offers.
Larger family sizes also influenced the likelihood of loan acceptance, suggesting targeted campaigns for larger households.
Younger customers (under 35) and older customers (over 60) showed distinct patterns, which could lead to age-specific marketing strategies.
Conclusion
This project provides actionable insights for AllLife Bank to optimize its marketing efforts and increase the conversion rate for personal loan products. The model helps prioritize resources for customers most likely to benefit from and accept loan offers.

Future Work
Expand the model by including more customer behavioral data.
Test with other algorithms such as Random Forest and SVM for improved accuracy.
Implement the model in production to automate customer targeting for future campaigns.
