# Telco Customer Churn Analysis 

## Overview
Interactive Tableau Public dashboard analyzing customer churn in a telecom company
using the Telco-Customer-Churn dataset. The goal is to identify which customers
leave and what factors drive churn.

🔗 **Live dashboard:** [View on Tableau Public](PASTE-YOUR-TABLEAU-PUBLIC-LINK-HERE)

## Files in this Repository
- `Tableau_Project_1_2026.twbx` — Tableau packaged workbook
- `Telco-Customer-Churn.csv` — source dataset

## Dataset
- **Source:** Telco-Customer-Churn (IBM sample dataset, via Kaggle)
- **Records:** ~7,000 customers
- **Key fields:** Contract, tenure, MonthlyCharges, InternetService, PaymentMethod, Churn

## KPIs
- Total Customers
- Churn Rate
- Total Monthly Revenue
- Avg Customer Tenure (months)
- Revenue at Risk (Churned)

## Visualizations
1. Churn Rate by Contract Type (bar chart)
2. Churn Count by Internet Service Type (stacked bar)
3. Tenure Distribution: Churned vs Retained (histogram)
4. Monthly Charges vs Tenure (scatter plot)
5. Churn Rate by Payment Method (horizontal bar)
6. Churn Rate by Demographics (grouped bar)
7. Add-on Services Adoption vs Churn (heat map)
8. Total Customers by Contract & Internet Service (treemap)

## Key Insights
- Overall churn rate: **XX%**
- **Contract type** is the strongest driver: month-to-month customers churn far more than 1- or 2-year contracts.
- **Fiber optic** customers churn more than DSL customers.
- **Electronic check** payers have the highest churn rate.
- Longer **tenure** is protective: most churn happens in the first months.
- **Senior citizens** churn at a higher rate.
- Customers **without add-on services** (e.g., Online Security, Tech Support) are more likely to leave.

## Calculated Fields
- **Churn Rate:** % of customers where Churn = "Yes"

## Tools
- Tableau Public
- GitHub

## Author
Surovi Jahan — [GitHub](https://github.com/SuroviJahan)
