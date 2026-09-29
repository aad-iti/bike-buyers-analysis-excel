# 🚴 Bike Buyers Analysis (Excel)

An end-to-end Excel analysis of bike buyer data: raw data cleaning, formatting, pivot tables and an interactive dashboard that shows which customers are most likely to buy a bike.

## 📸 Dashboard Preview

![Bike Buyers Dashboard](images/dashboard.png)

## 📌 Project Overview

A bike retailer wants to understand **who buys bikes and who does not**, so it can target marketing better. This project cleans the customer dataset, summarises it with pivot tables, and presents the results in a single dashboard built from those pivot tables.

## 🎯 Business Questions

- Which income groups buy the most bikes?
- Which age groups are the most likely to buy?
- Does commute distance affect bike purchases?
- How do purchases vary by region, occupation and education?
- Do marital status, gender, number of children or number of cars play a role?

## 🗂️ Dataset

- **Source file:** `data/bike_buyers_raw.xlsx`
- **Cleaned file:** `data/bike_buyers_clean.csv`
- **Size:** XXXX rows and XX columns
- **Target column:** `Purchased Bike` (Yes / No)
- **Other columns:** customer ID, marital status, gender, income, children, education, occupation, home owner, cars, commute distance, region and age

## 🧹 Data Cleaning & Formatting

1. Removed duplicate customer records
2. Checked for blank or missing values and handled them
3. Standardised inconsistent labels (for example, abbreviations such as M/S and M/F replaced with full text)
4. Fixed data types (income as currency, age as a number)
5. Created **age brackets** and **income brackets** to make grouping easier
6. Formatted the sheet as a table with clear headers so it works smoothly with pivot tables

## 📊 Analysis & Dashboard

Pivot tables were built from the cleaned data, and the dashboard was created using pivot charts based on them:

| Pivot table | Question answered |
|---|---|
| Purchases by income | Which income groups buy the most? |
| Purchases by age bracket | Which age groups are most likely to buy? |
| Purchases by commute distance | Does a shorter commute mean more bike buyers? |
| Purchases by region | Where are the buyers concentrated? |
| Purchases by occupation and education | Which professions and education levels buy more? |
| Purchases by marital status, gender, children and cars | Do household factors matter? |

## 💡 Key Insights

- **Income:** XX
- **Age:** XX
- **Commute distance:** XX
- **Region:** XX
- **Other factors:** XX

## 🧾 Recommendations

- Target marketing at the segments with the highest purchase rates
- Review the segments with low purchase rates to find out why they are not buying
- Track purchases by segment over time to measure the impact of campaigns

## 🛠️ Tools & Skills

**Microsoft Excel:** data cleaning, data formatting, formulas, pivot tables, pivot charts, dashboard design

## 📁 Repository Structure

```
bike-buyers-analysis-excel/
├── README.md
├── data/
│   ├── bike_buyers_raw.xlsx        # original dataset
│   └── bike_buyers_clean.csv       # cleaned dataset
├── dashboard/
│   └── bike_buyers_dashboard.xlsx  # pivot tables + dashboard
└── images/
    ├── dashboard.png
    └── pivot_tables.png
```

## ▶️ How to Use

1. Download `dashboard/bike_buyers_dashboard.xlsx`.
2. Open it in Excel. The **Dashboard** sheet shows the final view, and the other sheets contain the pivot tables and the cleaned data.

## 👩‍💻 Author

**Aaditi Ghogardare**
Data Eng, Mgmt and Governance Associate
🔗 [LinkedIn](https://www.linkedin.com/in/aaditi-ghogardare-634011212/) · 📧 aaditighogardare20502@gmail.com
