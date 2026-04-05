# Vrinda Store Annual Sales Analysis — 2022
> Analyzed 31,047 orders and ₹2.12 Cr in revenue across 7 sales channels using Excel to uncover customer behavior, channel performance, and regional trends for a women's fashion brand.

---

## Problem
Vrinda Store had a full year of transaction data but no clear picture of:
- Which sales channels drove the most revenue
- Who their core customers actually were (age + gender)
- Which states and product categories to prioritize in 2023

This project answers all three questions using Excel pivot tables, charts, and an interactive dashboard.

---

## Dataset
- **Source:** Vrinda Store internal transaction records
- **Size:** 31,047 rows | 21 columns
- **Period:** January 2022 – December 2022
- **Fields:** Order ID, Customer ID, Gender, Age, Age Group, Date, Channel, Category, Size, Quantity, Amount, Ship State, Order Status

---

## Tools Used
`Microsoft Excel` `Pivot Tables` `Pivot Charts` `Slicers` `Data Cleaning` `Dashboard Design`

---

## Process

1. **Data Understanding** — Explored 31,047 rows across 21 columns; identified key fields for analysis
2. **Data Cleaning** — Standardized Gender column (M→Men, W→Women), fixed inconsistent Month entries, removed blank rows
3. **Feature Engineering** — Created Age Group column (Teenager / Adult / Senior) from raw Age values
4. **Pivot Analysis** — Built 6 pivot tables: Sales by Month, Gender split, Age Group orders, Channel revenue, State-wise sales, Category breakdown
5. **Dashboard Design** — Combined all charts into a single-page interactive Excel dashboard with 4 slicers (Month, Gender, Age Group, Channel)
6. **Insights** — Derived 5 actionable business recommendations

---

## Dashboard Preview
<img width="1863" height="759" alt="Vrinda Store Sales Dashboard" src="https://github.com/user-attachments/assets/5f2cab01-e89b-45c4-8e36-89305194d9ff" />


---

## Key Findings

- **Women drive 69.6% of all orders** — men account for only 30.4%, confirming women are the primary customer base
- **Amazon is the #1 channel** with ₹75.2L revenue (35.5% of total), followed by Myntra (₹49.4L) and Flipkart (₹45.7L)
- **March is peak month** with ₹1.93M in sales — sales decline steadily from April through December
- **Maharashtra is the top state** (₹29.9L), followed by Karnataka (₹26.5L) and Uttar Pradesh (₹21.0L)
- **92.3% delivery rate** — only 2.7% cancelled, 3.4% returned, 1.7% refunded — strong fulfilment performance
- **"Set" is the best-selling category** at ₹1.05 Cr (49.7% of revenue), nearly double the second category (Kurta at ₹49.6L)
- **Adult women aged 25–45** place the highest volume of orders (43.6% of all orders)

---

## Business Recommendations

1. Increase Amazon and Myntra ad spend in Feb–Mar to capitalize on peak season
2. Launch targeted women's campaigns in Maharashtra, Karnataka, and UP — top 3 states by volume
3. Expand "Set" category inventory — it alone generates nearly half of total revenue
4. Introduce loyalty program for Adult women (25–45 age group) — the highest-value segment
5. Investigate Q4 revenue decline (Oct–Dec) — consider seasonal offers to recover lost sales

---

## Project Structure
```
vrinda-store-analysis/
├── Vrinda_Store_Data_Analysis.xlsx   # Main workbook (data + pivots + dashboard)
├── dashboard.png                      # Dashboard screenshot
└── README.md                          # This file
```

---

## Author
**Vijay Nirmalakar**
[[LinkedIn Profile](https://www.linkedin.com/in/vijaynirmalakar/)] | [[GitHub Profile](https://github.com/vijaynirmalakar)]

*Tools: Microsoft Excel | Skills: Data Cleaning, Pivot Tables, Dashboard Design, Business Analysis*
