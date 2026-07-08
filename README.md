# 📊 Customer Churn Analysis

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses such as OTT platforms, SaaS companies, telecom providers, and streaming services. This project analyzes customer behavior to identify churn patterns, measure customer retention, and generate actionable business insights that help organizations reduce customer churn.

The project uses customer, subscription, and support data stored in a SQLite database. The data is imported into Python for cleaning, feature engineering, exploratory data analysis (EDA), KPI calculation, and visualization.

---

## 🎯 Business Objective

The main objectives of this project are to:

- Identify churned customers.
- Measure overall churn and retention rates.
- Analyze churn across different subscription plans and regions.
- Identify high-risk customers.
- Estimate revenue at risk due to customer churn.
- Generate actionable recommendations to improve customer retention.

---

## 🛠️ Tools & Technologies

- Python
- SQLite (Database)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses a SQLite database (**customer_churn.db**) containing three related tables:

### Customer Table
- Customer ID
- Customer Name
- Country
- State
- Gender
- Date of Birth

### Subscription Table
- Subscription Start Date
- Subscription Type
- Plan Type
- Contract Type
- Monthly Charges
- Customer Lifetime Value (CLTV)
- Churn Score
- Cancellation Details

### Support Table
- Complaint Date
- Escalation Status
- Customer Satisfaction (CSAT)

---

## 📈 Project Workflow

### 1️⃣ Data Import
- Connected Python to a SQLite database using `sqlite3`.
- Imported customer, subscription, and support tables into Pandas DataFrames.
- Merged the datasets using Customer ID.

### 2️⃣ Data Cleaning
- Renamed columns.
- Removed unnecessary columns.
- Converted date columns into datetime format.
- Standardized gender values.
- Filled missing values.
- Removed duplicate records.

### 3️⃣ Feature Engineering
Created new business features such as:
- Churn Flag
- Complaint Count
- Customer Tenure
- Churn Risk Category

### 4️⃣ Exploratory Data Analysis
Calculated key business metrics including:
- Churn Rate
- Retention Rate
- Churn by Plan Type
- Churn by State
- Revenue at Risk
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Escalation Rate
- Average Complaints per Customer
- Correlation between Escalations and Churn

### 5️⃣ Data Visualization
Created visualizations using Matplotlib and Seaborn:
- Monthly Churn Trend
- Churn Rate by Plan Type
- Churn by State
- Correlation Heatmap
- Pair Plot
- Category-wise Analysis

---

## 📊 Key Findings

- Overall Churn Rate: **28.57%**
- Retention Rate: **71.43%**
- Basic subscription plans experienced the highest churn.
- Karnataka recorded the highest churn rate.
- Monthly contract customers churned more than annual contract customers.
- Average Revenue Per User (ARPU): **18.85**
- Average Customer Tenure: **Approximately 1,490 days**
- Revenue at Risk due to churn: **73.94**
- Customer escalations showed a strong positive relationship with churn.

---

## 💡 Business Recommendations

- Improve customer experience for Basic plan subscribers.
- Investigate the reasons behind high churn in Karnataka.
- Encourage customers to switch from monthly to annual subscription plans.
- Prioritize customers with High and Medium churn risk.
- Resolve customer complaints quickly.
- Monitor customer satisfaction and escalation trends regularly.

---


## 📌 Skills Demonstrated

- Python Programming
- SQLite Database Connectivity
- Data Cleaning
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- KPI Development
- Data Visualization
- Customer Analytics
- Business Intelligence

---

## 👨‍💻 Author

**Ramesh Chulbule**
