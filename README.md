# Financial Fraud Detection Model with Dashboard

## 📌 Project Overview

The **Financial Fraud Detection Model with Dashboard** is a data science and machine learning project designed to identify potentially fraudulent financial transactions and provide analytical insights through an interactive Power BI dashboard.

The project combines:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Fraud Probability Prediction
- Risk Classification
- Reinforcement Learning-based transaction decisions
- Fraud Monitoring and Alerting
- Interactive Power BI Dashboard

The system analyzes transaction-related information such as transaction amount, merchant category, payment method, device type, location, international transactions, previous transactions, average spending, account age, and suspicious keywords.

---

## 🎯 Objectives

The main objectives of this project are:

1. Clean and preprocess financial transaction data.
2. Perform exploratory data analysis to understand transaction and fraud patterns.
3. Create meaningful features for fraud detection.
4. Train multiple machine learning models for fraud classification.
5. Generate fraud probabilities for transactions.
6. Classify transactions into different risk levels.
7. Apply a reinforcement learning-based decision layer for transaction actions.
8. Generate monitoring and alert information.
9. Provide an interactive Power BI dashboard for analysis and investigation.

---

## 🛠️ Technologies Used

### Programming & Data Science

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### Reinforcement Learning

- Q-Learning
- States
- Actions
- Rewards
- Q-Table

### Dashboard

- Microsoft Power BI

### Alerting

- Python `smtplib`
- Gmail SMTP

---

## 📂 Project Structure

```text
Financial-Fraud-Detection/
│
├── dashboard/
│   └── Financial_Fraud_Detection_Dashboard.pbix
│
├── data/
│   ├── raw/
│   │   └── financial_fraud_detection_dataset.csv
│   │
│   └── cleaned/
│       ├── financial_fraud_clean.csv
│       ├── fraud_features.csv
│       ├── fraud_predictions.csv
│       └── fraud_monitoring.csv
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Fraud_Detection.ipynb
│   └── 05_Fraud_Analysis.ipynb
│
├── Project Report/
│   ├── Financial Fraud Detection - Project Report - Kaushik Wadhavana.docx
│   └── Financial Fraud Detection - Project Report - Kaushik Wadhavana.pdf
│
└── README.md
