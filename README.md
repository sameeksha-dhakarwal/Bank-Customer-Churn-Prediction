# Bank-Customer-Churn-Prediction
Customer churn is one of the biggest challenges faced by banks and financial institutions.  
This project focuses on building a **Bank Customer Churn Prediction system** that identifies customers who are likely to leave the bank, enabling proactive retention strategies.
Using **Machine Learning and Deep Learning techniques**, the model analyzes customer demographic, behavioral, and financial data to predict churn probability.

---

## Problem Statement
To predict whether a bank customer will **exit (churn)** or **stay**, based on historical customer data such as:
- Credit score
- Age
- Tenure
- Balance
- Product usage
- Activity status
- Estimated salary

---

## Dataset
- **Source:** Kaggle – Bank Customer Churn Dataset 
- **Target Variable:** `Exited`  
  - `1` → Customer churned  
  - `0` → Customer stayed  

### Key Features
- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `IsActiveMember`
- `EstimatedSalary`

---

## Feature Engineering
Additional features were created to improve prediction performance:
- **Transaction Frequency**
- **Recent Large Withdrawals**
- **Customer Loyalty Score**

---

## Models Implemented
The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Artificial Neural Network (ANN)

---

## Evaluation Metrics
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- ROC–AUC Score
- ROC Curves for model comparison

---

## Results
- Ensemble and deep learning models performed better than baseline models.
- ANN and XGBoost achieved higher ROC-AUC scores.
- The system can rank customers based on **churn probability**, helping banks prioritize high-risk customers.

---

## 🛠️ Tech Stack

### Programming Languages
- Python

### Libraries & Frameworks
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- XGBoost

### Tools
- VS Code
- Git & GitHub

---
