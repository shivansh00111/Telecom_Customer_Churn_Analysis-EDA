# Telecom Customer Churn Analysis – Exploratory Data Analysis 📞📉

This project performs a detailed exploratory data analysis (EDA) on a telecom dataset to identify key factors that influence customer churn and help improve retention strategies.

---

## 🎯 Problem Statement

Customer churn is a major concern for telecom companies. The aim of this project is to explore the dataset and uncover the reasons why customers are leaving, enabling the business to take proactive steps toward customer retention.

---

## 📁 Dataset Overview

- **Source**: Provided CSV file (e.g., `telecom_churn.csv`)
- **Records**: Over 7,000 customer profiles
- **Features Include**:
  - Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Services: `PhoneService`, `InternetService`, `OnlineSecurity`, `StreamingTV`
  - Account info: `tenure`, `Contract`, `MonthlyCharges`, `TotalCharges`
  - Target: `Churn` (Yes/No – whether the customer left)

---

## 🧰 Tools and Libraries

- Python 3.x
- pandas, NumPy – data wrangling
- seaborn, matplotlib – data visualization
- Jupyter Notebook – EDA notebook execution

---

## 🧪 Analysis Steps

1. **Data Cleaning**
   - Checked for missing values and data types
   - Handled whitespace and string inconsistencies in `TotalCharges`
   - Converted numerical and categorical features appropriately

2. **Univariate Analysis**
   - Distribution plots for `tenure`, `MonthlyCharges`, `TotalCharges`
   - Count plots for `gender`, `Partner`, `Contract`, etc.

3. **Bivariate Analysis**
   - Churn rate comparison across service types and demographics
   - Contract type, senior citizenship, and online security impact on churn

4. **Multivariate Relationships**
   - Heatmap for correlation
   - Tenure and contract duration effects on customer retention

5. **Visual Insights**
   - Custom bar plots, violin plots, pie charts to understand patterns

---

## 💡 Key Insights

- Customers on month-to-month contracts churn the most.
- Lack of internet security and tech support correlates with higher churn.
- Senior citizens and single customers are more likely to leave.
- Longer tenure customers are generally retained better.

---

## 📂 Project Structure

```
├── telecom_churn.csv                       # Dataset
├── Telecom_Churn_EDA.ipynb                 # Notebook with full analysis
├── README.md                               # Project summary (this file)
└── Telecom_Churn_EDA_Report.pdf            # Summary report with visuals
```

---

*Created by Shivansh – explore the notebook and insights to understand churn drivers.*