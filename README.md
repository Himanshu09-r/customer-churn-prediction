# 📊 Customer Churn Prediction

## 🚀 Project Overview

Customer churn refers to customers who discontinue or cancel a service.

This project analyzes telecom customer behavior and builds a machine learning model to predict customer churn.

### 🎯 Objectives
- Understand why customers leave  
- Identify key churn-driving factors  
- Enable data-driven customer retention strategies  

---

## 📂 Dataset

- **Name:** Telco Customer Churn Dataset  
- **Source:** IBM Sample Dataset (Kaggle)  
- **Total Records:** 7,043 customers  
- **Target Variable:** `Churn` (Yes / No)

### Dataset Contains:
- Customer demographic details  
- Service usage information  
- Contract type details  
- Billing and payment information  
- Tenure data  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔎 Key Observations

- Overall churn rate ≈ **26.5%**  
- Customers with shorter tenure are more likely to churn  
- Higher monthly charges are associated with higher churn  
- Month-to-month contracts show highest churn  
- Customers with partners/dependents are more stable  

---

## 🧹 Data Quality Handling

- Identified `TotalCharges` stored as text  
- Converted `TotalCharges` to numeric  
- Handled missing values  
- Verified dataset consistency  

---

## ⚙️ Data Preprocessing

### ✔ Data Cleaning
- Removed `customerID`  
- Converted `Churn` to binary (1 = Yes, 0 = No)  
- Handled missing values  

### ✔ Feature Engineering
- Applied Binary Encoding  
- Applied One-Hot Encoding  
- Validated transformed dataset  

---

## 🏗 Project Workflow

1. Dataset Loading  
2. Exploratory Data Analysis  
3. Data Cleaning  
4. Feature Encoding  
5. Feature Scaling  
6. Train-Test Split  
7. Model Training  
8. Model Evaluation  

---

## 📌 Current Status

- ✔ EDA Completed  
- ✔ Data Cleaning Completed  
- ✔ Feature Engineering Completed  
- 🔄 Model Training in Progress  

---

## 🚀 Next Steps

- Feature Scaling  
- Train-Test Split  
- Logistic Regression (Baseline Model)  
- Model Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)  
- Model Optimization  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib   
- Scikit-learn  
