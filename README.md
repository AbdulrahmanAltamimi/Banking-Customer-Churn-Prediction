# Banking-Customer-Churn-Prediction
Banking Customer Churn Prediction
Project Overview
This project develops a machine learning pipeline to predict customer churn (churn vs. non-churn). Customer churn prediction is vital for identifying customers at risk of leaving and taking proactive measures to retain them.

Key Features:
Modeling Techniques:
Random Forest for interpretable, tree-based classification.
Neural Network for deep learning, implemented with TensorFlow.
Support Vector Machine (SVM) for linear and non-linear classification.
Comprehensive evaluation of model performance using metrics such as Accuracy and AUPRC.
Tools and Libraries
Programming Language: Python
Libraries:
TensorFlow: For building and training deep learning models.
Scikit-learn: For Random Forest, SVM, and preprocessing utilities.
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Matplotlib and Seaborn: For data visualization.
Dataset
The dataset contains banking customer data with features such as demographics, transaction history, and account details. The target variable indicates churn (1) or non-churn (0).

the link for dataset: https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset
Example Features:
Demographics: Age, Gender, etc.
Account Information: Balance, Transactions, etc.
Behavioral Insights: Tenure, Credit Score, etc.
Workflow
Data Preprocessing:
Handling missing values and outliers.
Encoding categorical variables.
Feature scaling and normalization.
Exploratory Data Analysis (EDA):
Analyzing correlations and distributions.
Visualizing feature importance.
Model Development:
Building a Neural Network and training a Random Forest using TensorFlow.
Implementing an SVM classifier with Scikit-learn.
Evaluation:
Comparing model performance using metrics like:
Accuracy
F1-Score
ROC-AUC
AUPRC