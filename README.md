# Customer Churn Prediction

## Project Overview
Customer churn refers to customers who discontinue or cancel a service.  
This project aims to analyze customer behavior and build a machine learning model to predict customer churn in a telecom company.

The focus is on understanding **why customers leave** and identifying key factors that influence churn.

---

## Dataset
- **Name:** Telco Customer Churn Dataset
- **Source:** IBM Sample Dataset (Kaggle)
- **Records:** 7,043 customers
- **Target Variable:** Churn (Yes / No)

The dataset contains customer demographic details, service usage, billing information, and contract details.

---

## Exploratory Data Analysis (Day 1)

### Key Observations
- Overall churn rate is approximately **26.5%**, indicating a significant churn problem.
- Customers with **shorter tenure** are more likely to churn.
- **Higher monthly charges** are associated with higher churn.
- **Month-to-month contracts** show the highest churn compared to long-term contracts.
- Customers with partners or dependents tend to be more stable.

### Data Quality Handling
- Identified `TotalCharges` as a numeric column stored as text.
- Converted `TotalCharges` to numeric format and handled missing values appropriately.

---

## Current Status
- ✔ Dataset loaded and understood
- ✔ Exploratory Data Analysis completed
- ✔ Key churn-driving factors identified

---

## Next Steps
- Data cleaning and preprocessing
- Encoding categorical features
- Train-test split
- Build and evaluate a churn prediction model

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
