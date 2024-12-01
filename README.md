# Banking Customer Churn Prediction Project

## Overview
This project develops a machine learning pipeline to predict customer churn (churn vs. non-churn). Customer churn prediction is vital for identifying customers at risk of leaving and taking proactive measures to retain them.

---

## Key Features

### Modeling Techniques:
- **Random Forest**: Interpretable, tree-based classification.
- **Neural Network**: Deep learning model implemented with TensorFlow.
- **Support Vector Machine (SVM)**: For linear and non-linear classification.
- **Evaluation Metrics**:
  - Accuracy
  - AUPRC (Area Under Precision-Recall Curve)

---

## Tools and Libraries

### Programming Language:
- **Python**

### Libraries:
- **TensorFlow**: For building and training deep learning models and Random Forest.
- **Scikit-learn**:  SVM, and preprocessing utilities.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.

---

## Dataset

The dataset contains banking customer data with features such as demographics, transaction history, and account details. The target variable indicates **churn (1)** or **non-churn (0)**.

- **Dataset Link**: [Bank Customer Churn Prediction Dataset](https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset)

### Example Features:
1. **Demographics**: Age, Gender, etc.
2. **Account Information**: Balance, Transactions, etc.
3. **Behavioral Insights**: Tenure, Credit Score, etc.

---

## Workflow

### 1. **Data Preprocessing**
   - Handling missing values and outliers.
   - Encoding categorical variables.
   - Feature scaling and normalization.

### 2. **Exploratory Data Analysis (EDA)**
   - Analyzing correlations and distributions.
   - Visualizing feature importance.

### 3. **Model Development**
   - **Neural Network**: Built and trained using TensorFlow.
   - **Random Forest**: Implemented with Scikit-learn.
   - **SVM Classifier**: Built with Scikit-learn.

### 4. **Evaluation**
   - Comparing model performance using:
     - Accuracy
     - F1-Score
     - ROC-AUC (Receiver Operating Characteristic - Area Under Curve)
     - AUPRC (Area Under Precision-Recall Curve)

---
