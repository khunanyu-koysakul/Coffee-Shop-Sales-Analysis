# ☕ Coffee Shop Sales Analysis

## Overview
This project analyzes coffee shop transaction data to understand customer behavior, product performance, and operational efficiency.  
The goal is to provide business recommendations to increase revenue without increasing customer traffic.

---

## Business Problem
The coffee shop experiences heavy morning traffic but significantly lower sales later in the day.  
Additionally, customers usually purchase only one item per visit, limiting revenue per customer.

---

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Insights

### Peak Hours
Sales consistently peak between 8 AM – 10 AM across all days.

### Customer Spending
Average Order Value: **$4.69**  
Average Items per Order: **1.4 items**

Customers typically purchase only one drink per visit.

### Product Performance
Coffee beverages generate most of the revenue, while several categories contribute very little.

### Demand Imbalance
Sales drop significantly after 11 AM, leaving store capacity underutilized.

---

## Business Recommendations
- Increase staff during morning peak hours
- Introduce bundle promotions (drink + bakery)
- Promote different menu items based on time of day
- Apply afternoon promotions to balance sales
- Simplify low-performing menu items

---

## Project Structure
coffee-shop-sales-analysis
│
├── data/
│   └── coffee_shop_sales.csv
│
├── notebooks/
│   └── coffee_sales_analysis.ipynb
│
├── images/
│   └── (exported visualizations)
│
├── README.md
├── requirements.txt
└── .gitignore
