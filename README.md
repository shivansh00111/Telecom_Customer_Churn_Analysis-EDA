# Bank Term Deposit Campaign – Exploratory Data Analysis 📊

A detailed EDA on marketing campaign data from a Portuguese bank, aimed at understanding factors that influence customer subscription to term deposits.

---

## 🎯 Problem Statement

The bank launched a marketing campaign to promote term deposit subscriptions through phone calls. The objective of this project is to analyze customer and campaign features to identify key patterns associated with successful subscriptions.

---

## 📁 Dataset Overview

- **Source**: Provided CSV (`bank_marketing_updated_v1.csv`)
- **Records**: 45,213 customer entries
- **Features Include**:
  - Customer demographics: `age`, `marital`, `salary`, `jobedu`
  - Financial details: `balance`, `loan`, `housing`, `default`
  - Campaign info: `contact`, `duration`, `pdays`, `previous`, `poutcome`
  - **Target**: `response` (yes/no – term deposit subscription)

---

## 🧰 Tools and Libraries

- Python 3.x
- pandas, NumPy – data cleaning and transformation
- matplotlib, seaborn – visualizations
- Jupyter Notebook – interactive analysis

---

## 🧪 Analysis Steps

1. **Data Cleaning**
   - Skipped non-data header rows
   - Renamed columns and fixed formatting
   - Handled missing/null values

2. **Univariate Analysis**
   - Distribution plots for `age`, `salary`, `balance`
   - Count plots for `marital`, `housing`, `jobedu`, `contact`

3. **Bivariate Analysis**
   - Analyzed impact of customer features on `response`
   - Bar plots for categorical feature conversion rates

4. **Multivariate Observations**
   - Call duration and contact month correlation with conversion
   - Effect of prior contact outcome (`poutcome`) on success

5. **Visual Summaries**
   - Plotted histograms, bar charts, and correlation heatmaps

---

## 💡 Key Insights

- Customers with specific job types (e.g., admin, student) showed higher response rates.
- Longer call durations tended to result in more successful subscriptions.
- Customers without personal or housing loans responded more positively.
- Campaigns using personal contacts performed better than unknown contact types.

---

## 📂 Project Structure

```
├── bank_marketing_updated_v1.csv         # Input dataset
├── EDA_Code.ipynb                        # Jupyter notebook with full analysis
├── README.md                             # Project summary (this file)
├── Bank_Campaign_EDA_Case_Study_Report.pdf  # Summary report with visuals
```

---

*Developed by Shivansh – explore the notebook and report for full insight.*