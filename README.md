# 📉 Customer Churn Analysis | Telecom EDA Project

> **Python · Pandas · Matplotlib · Seaborn · Exploratory Data Analysis**

An end-to-end exploratory data analysis project on a telecom customer dataset to identify who is churning, why, and what patterns predict attrition — delivering actionable insights for customer retention strategy.

---

## 📌 Problem Statement

Customer churn is one of the most costly problems in the telecom industry. Acquiring a new customer costs significantly more than retaining an existing one. This project analyzes a dataset of 7,000+ telecom customers to identify the key drivers of churn across demographics, contract types, service usage, and payment behavior — enabling data-driven retention decisions.

---

## 📊 Dataset Summary

| Attribute | Detail |
|-----------|--------|
| Total Records | 7,043 customers |
| Target Variable | Churn (Yes / No) |
| Overall Churn Rate | 26.54% |
| Features | 21 columns — demographics, services, contract, billing |

---

## 🔍 Key Findings

- **26.54%** of customers have churned — 1 in 4 customers is leaving.
- **Month-to-month contract** customers churn at a dramatically higher rate than 1 or 2 year contract holders.
- **New customers (0–2 months tenure)** show the highest churn spike — early retention is critical.
- **Senior citizens** churn at a proportionally higher rate than non-senior customers.
- **Fiber optic internet** users churn more than DSL users despite higher service usage.
- **Gender has no significant impact** on churn — male and female churn rates are nearly identical.

---

## 📈 Visualizations

### Churn Distribution
![Churn Count and Percentage](Screenshot%202026-05-28%20012835.png)

### Churn by Gender & Senior Citizen
![Churn by Gender and Senior Citizen](Screenshot%202026-05-28%20012854.png)

### Churn by Tenure & Contract Type
![Churn by Tenure and Contract](Screenshot%202026-05-28%20012926.png)

### Service Feature Distributions
![Customer Churn Service Feature Distributions](Screenshot%202026-05-28%20013000.png)

---

## 🏗️ Project Structure

```
Customer_Churn_Analysis/
├── Customer_churn.csv
├── customer_churn_analysis.ipynb
└── README.md
```

---

## ⚙️ Approach

**Step 1 — Data Loading & Inspection**
- Loaded dataset, inspected shape, dtypes, and null values
- Identified and resolved data quality issues

**Step 2 — Data Cleaning & Wrangling**
- Handled missing values in TotalCharges column
- Corrected datatypes and standardized categorical variables
- Converted binary columns for analysis readiness

**Step 3 — Exploratory Data Analysis**
- Analyzed churn distribution and overall churn rate
- Explored churn across demographics — gender, senior citizen status
- Analyzed behavioral patterns — tenure, contract type, payment method
- Examined service usage patterns — internet, security, streaming

**Step 4 — Visual Storytelling**
- Built 15+ visualizations using Matplotlib and Seaborn
- Used count plots, bar charts, histograms, pie charts, and heatmaps
- Added data labels and annotations for business readability

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core analysis language |
| Pandas | Data cleaning and wrangling |
| NumPy | Numerical operations |
| Matplotlib | Base visualizations |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Analysis environment |

---

## 🎯 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Customer segmentation and behavioral analysis
- Business insight communication through visualization
- Retention-focused analytical thinking

---

## 👤 Author

Saket Tripathi
📧 saket08004@gmail.com
🔗 [linkedin.com/in/saket-tripathi](https://linkedin.com/in/saket-tripathi)
🐙 [github.com/saket08004](https://github.com/saket08004)
