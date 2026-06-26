# Credit Risk Modeling

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange">
  <img src="https://img.shields.io/badge/Streamlit-Web%20App-red">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

<p align="center">
<b>Predicting customer creditworthiness using Machine Learning and the German Credit Dataset.</b>
</p>

---

# 📌 Project Overview

Credit risk assessment is one of the most important tasks in the banking and financial industry. Financial institutions need to determine whether a customer is likely to repay a loan or become a credit risk.

This project builds a Machine Learning model to classify customers based on their financial and demographic information and predict whether they represent a good or bad credit risk.

The project includes:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Credit Risk Prediction
* Streamlit Web Application Deployment

---

# 🎯 Business Problem

Banks and lending institutions face significant financial losses due to loan defaults.

Manual credit assessment:

* Is time-consuming
* Can be subjective
* May overlook important patterns in customer data

The objective of this project is to develop a data-driven system that can:

* Predict customer credit risk
* Improve lending decisions
* Reduce loan default rates
* Support faster loan approvals

---

# 🚀 Objectives

* Analyze customer credit data
* Build a predictive machine learning model
* Classify customers into credit risk categories
* Deploy the model using Streamlit
* Generate predictions in real time

---

# 📂 Dataset Information

Dataset Used:

**German Credit Dataset**

The dataset contains customer information such as:

* Age
* Sex
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration
* Job Information
* Risk Category

Dataset File:

```text
german_credit_data.csv
```

Update with actual values:

* Number of Records: 1000
* Number of Features: 11

---

# 🛠️ Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| Pandas           | Data Manipulation       |
| NumPy            | Numerical Computing     |
| Matplotlib       | Data Visualization      |
| Seaborn          | Data Visualization      |
| Scikit-Learn     | Machine Learning        |
| Streamlit        | Web Application         |
| Pickle           | Model Serialization     |
| Jupyter Notebook | Development Environment |

---

# 📊 Project Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Categorical Encoding
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Credit Risk Prediction
        ↓
Streamlit Deployment
```

---

# 🔍 Exploratory Data Analysis

Performed analyses such as:

* Age Distribution
* Credit Amount Distribution
* Gender Analysis
* Risk Distribution
* Correlation Analysis
* Categorical Feature Analysis

---

# 🤖 Machine Learning Model

## Algorithm Used

**Extra Trees Classifier**

Why Extra Trees?

* Handles complex relationships well
* Reduces overfitting
* High predictive performance
* Fast training and prediction

---

# ⚙️ Model Pipeline

1. Data Cleaning
2. Handling Missing Values
3. Label Encoding
4. Feature Selection
5. Model Training
6. Model Serialization using Pickle
7. Streamlit Deployment

---

# 📈 Expected Output

The model predicts:

* Good Credit Risk
* Bad Credit Risk

The prediction can assist banks in:

* Loan Approval Decisions
* Risk Management
* Customer Profiling

---

# 📸 Application Screenshots

## 🏠 Home Page


<img width="1917" height="1030" alt="image" src="https://github.com/user-attachments/assets/a0f979b5-f15e-49d9-85cf-69afd1f9af65" />



---

## 📊 Prediction Result

<img width="667" height="827" alt="image" src="https://github.com/user-attachments/assets/48738d1d-0e2a-464a-a10d-83175cbfdac6" />

---

# 📁 Project Structure

```text
Credit-Risk-Modeling/
│
├── app.py
├── credit-risk.ipynb
├── german_credit_data.csv
├── extra_trees_credit_model.pkl
│
├── Checking account_encoder.pkl
├── Saving accounts_encoder.pkl
├── Housing_encoder.pkl
├── Sex_encoder.pkl
├── target_encoder.pkl
│
├── requirements.txt
├── README.md
│
└── images/
    ├── home_page.png
    ├── input_form.png
    └── prediction_result.png
```

---

# 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
streamlit
jupyter
```

---

# 💡 Business Impact

This project can help financial institutions:

* Improve loan approval decisions
* Reduce financial losses
* Automate risk assessment
* Improve customer screening efficiency

---

# 🔮 Future Improvements

* Deploy on Streamlit Cloud
* Add probability scores
* Explain predictions using SHAP
* Hyperparameter tuning
* Compare multiple classification models
* Add model monitoring dashboard

---

# 🏆 Key Learnings

Through this project, I learned:

* Classification Algorithms
* Feature Engineering
* Handling Categorical Variables
* Model Deployment with Streamlit
* Pickle Serialization
* Financial Risk Analytics
* End-to-End Machine Learning Workflow

---

# 👨‍💻 Author

**Aditya Singh**

GitHub:
https://github.com/AdityaDev-17

LinkedIn:
https://www.linkedin.com/in/YOUR-LINKEDIN/

---
