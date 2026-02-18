# 📉 Customer Churn Analysis

This project analyzes customer churn patterns for a telecom dataset using Python (Pandas, Numpy, Matplotlib, Seaborn). The goal is to identify factors influencing churn and provide actionable insights to improve retention.

## 🔹 Project Workflow

### 1. Data Preprocessing

    - Loaded dataset (Customer Churn.csv).

    - Cleaned missing values and converted data types (e.g., TotalCharges).

### 2.Exploratory Data Analysis (EDA)

    - Overall churn rate: ~26.5% customers churned.

    - Key insights:

          - Senior citizens are more likely to churn.

          - Customers with short tenure (1–2 months) churn more than long-term users.

          - Month-to-month contracts have higher churn compared to 1-year or 2-year contracts.

          - Customers with PhoneService, DSL Internet, OnlineSecurity are more loyal.

          - Churn is higher when services like TechSupport, OnlineBackup, StreamingTV are not used.

          - Customers using Electronic Check as a payment method churn at higher rates.

### 3.Visualization

    - Pie charts for churn distribution.

    - Bar plots for contract type vs churn.

    - Service usage impact on churn.

    - Payment method impact on churn.

### 🚀 Tech Stack

    - Python → Data analysis & visualization.

    - Pandas, NumPy → Data cleaning & preprocessing.

    - Matplotlib, Seaborn → Exploratory visualization.

### 📈 Key Insights

    - Long-term contracts and bundled services reduce churn probability.

    - Senior citizens and short-tenure users require targeted retention strategies.

    - Incentives for switching from Electronic Check to more stable payment methods can help reduce churn.
