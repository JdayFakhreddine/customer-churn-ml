# 📊 Customer Churn Prediction – Machine Learning Project

## 📌 Project Overview

This project aims to predict customer churn for a telecommunications company using Machine Learning.

Customer churn prediction is a critical business problem because retaining existing customers is significantly cheaper than acquiring new ones. By identifying customers at risk of leaving, companies can take proactive actions to improve retention.

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA)
* Clean and preprocess real-world data
* Build and evaluate Machine Learning models
* Handle class imbalance issues
* Interpret results from a business perspective

---

## 📂 Dataset

The dataset contains customer information including:

* Demographics (gender, senior citizen, partner)
* Subscription details (internet service, contract type)
* Financial data (monthly charges, total charges)
* Target variable: **Churn (Yes / No)**

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 🔎 Project Workflow

### 1. Exploratory Data Analysis (EDA)

We analyzed:

* Distribution of churn vs non-churn
* Relationship between churn and services
* Numerical feature distributions
* Outliers using boxplots

Purpose:
To understand data patterns and identify key variables.

---

### 2. Data Cleaning

Steps performed:

* Converted data types
* Handled missing values
* Removed irrelevant columns

Purpose:
Ensure data quality before modeling.

---

### 3. Feature Engineering & Encoding

Categorical variables were transformed using One-Hot Encoding.

Purpose:
Machine Learning models require numerical inputs.

---

### 4. Feature Scaling

StandardScaler was applied to normalize numeric features.

Purpose:
Prevent features with large values from dominating the model.

---

## 🤖 Models Implemented

### Logistic Regression

Baseline model for binary classification.

### Random Forest Classifier

Advanced ensemble model capable of capturing complex relationships.

---

## 📊 Model Evaluation Metrics

We evaluated models using:

* Accuracy
* Precision
* Recall (most important for churn)
* F1-Score

---

## ⚖️ Handling Class Imbalance

The dataset contained more non-churn than churn customers.

To improve churn detection, we adjusted the classification threshold from **0.5 to 0.3**.

---

## 📈 Results

### Final Model Performance

* Accuracy: **77%**
* Churn Recall: **77%**

This means the model successfully identifies most customers likely to leave.

---

## 🔑 Key Factors Influencing Churn

Top drivers identified by the model:

* Fiber optic internet service
* High total charges
* Electronic check payment method
* Paperless billing
* Streaming services

---

## 💼 Business Recommendations

Based on insights:

* Monitor customers with high bills
* Encourage automatic payment methods
* Offer retention promotions to high-risk customers
* Improve fiber internet service experience

---

## 🚀 Skills Demonstrated

This project demonstrates:

* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Machine learning modeling
* Model evaluation and tuning
* Business interpretation of results

---




