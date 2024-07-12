# Analytics_In_Finance
**Abstract**

Banks receive numerous applications for credit cards, each requiring careful evaluation based on applicant attributes and historical credit data. Manual assessment is prone to errors and time-consuming. This project leverages machine learning techniques to automate the credit card approval process, aiming to assist financial institutions in making informed decisions efficiently.

**Problem Statement**

The objective is to develop a predictive model that accurately determines whether a credit card application should be approved or rejected. By analyzing various applicant attributes and historical credit data, the model aims to minimize the risk of default and maximize profitability for financial institutions.

**Scope**

Exploratory Data Analysis (EDA): Gain insights into the dataset through statistical summaries and visualizations.
Model Development: Train and evaluate classification algorithms to predict credit card approval decisions.
Feature Importance: Analyze the significance of different features in predicting approval outcomes and optimize the model accordingly.
Model Evaluation: Assess model performance using metrics such as accuracy, precision, recall, and F1-score.

**Objective & Learning Outcome**

The goal is to train a machine learning model that generalizes well to new data, providing reliable predictions of credit card approval. Learners will gain proficiency in:
Building and evaluating classification models.
Performing EDA to understand data characteristics.
Iteratively improving model performance through feature engineering and parameter tuning.

**Conclusion**

The developed model achieved an overall accuracy of 87.68%, with a precision of 90.31% for approving credit card applications correctly and a recall of 96.12% for correctly identifying actual approvals. However, it showed lower precision (32.15%) in rejecting applications correctly. The F1-score of 93.12% indicates a good balance between precision and recall.
It's important to note the dataset imbalance (87% good payers vs. 13% bad profiles) and the absence of applicants denied for reasons like unpaid debts, potentially impacting real-world model performance. Future improvements could focus on enhancing the model's ability to correctly reject applications and addressing dataset biases.
