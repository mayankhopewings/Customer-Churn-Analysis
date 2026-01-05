# Customer Churn Analysis

## 📌 Overview
This analysis explores customer behavior to understand why customers churn and identifies the key factors that influence churn.

## 🎯 Objective
- Understand churn patterns
- Identify important churn drivers
- Build a predictive model for churn

## 📊 Dataset
- Source: Telco customer data
- Rows: ~7,000 customers
- Target: StateNextMonth (0 = No Churn, 1 = Churn)

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Key Steps
1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Encoding
4. Train-Test Split
5. Model Training (Logistic Regression)
6. Model Evaluation
7. Feature Importance

## 💡 Key Insights
- Month-to-month customers churn more.
- Customers with shorter tenure churn more.
- Higher monthly charges are associated with higher churn.

## 📈 Model Performance
- Accuracy: ~86%
- ROC AUC: ~0.87

## 📌 Conclusion
The analysis shows that contract type, tenure, and monthly charges strongly affect churn. Businesses can reduce churn by focusing on these high-risk groups.

