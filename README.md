# 📱 Mobile Sales Analytics — Power BI Project

## 1. Project Overview

**Mobile Sales Analytics** is an interactive Power BI project created to analyze mobile-phone sales performance across sales value, quantity, transactions, brands, mobile models, cities, payment methods, customer ratings, and time.

The Excel source contains **3,835 transactions** covering **2021–2024**.

### Business Objective

The dashboard is designed to answer:
- How much sales value is being generated?
- How many units and transactions are being recorded?
- How is sales performance changing over time?
- Which brands and mobile models generate the most sales?
- Which cities contribute most to sales?
- Which payment methods are used most frequently?
- What is the customer rating distribution?
- How does a year compare with the same period in the previous year?

## 2. Tools & Technologies

- Microsoft Excel — source dataset
- Power BI Desktop — dashboard development
- Power Query — data preparation
- DAX — KPI and time-intelligence calculations
- Power BI Slicers — interactive filtering

## 3. Dataset Overview

| Metric | Value |
|---|---:|
| Total Transactions | 3,835 |
| Total Units Sold | 19,150 |
| Total Sales | ₹769.20M |
| Average Price per Unit | ₹40,114.04 |
| Brands | 5 |
| Mobile Models | 15 |
| Cities | 19 |
| Payment Methods | 4 |
| Years | 2021–2024 |

**Sales calculation:** `Units Sold × Price Per Unit`

---

# 4. Dashboard 1 — Mobile Sales Dashboard

### Purpose

Provides an overall view of mobile sales performance. Users can filter the report by **Mobile Model, Payment Method, Brand and Month**.

### KPI Cards

**Total Sales** — total sales value for the selected filters.  
**Business question:** How much sales value has been generated?

**Total Quantity** — total mobile units sold.  
**Business question:** How many units have been sold?

**Transaction** — number of sales transactions.  
**Business question:** How many transactions were completed?

**Average Price** — average selling price per unit.  
**Business question:** What is the average price of mobiles sold?

### Visuals and Business Questions

| Visual | Purpose | Business Question |
|---|---|---|
| Total Sales by City — Map | Geographic sales distribution | Which cities generate the most sales? |
| Total Quantity by Month — Line Chart | Monthly trend | Which months have higher unit sales? |
| Ratings by Rating Status | Customer satisfaction summary | What is the distribution of Good/Average/Poor ratings? |
| Transaction by Payment Method — Pie Chart | Payment channel comparison | Which payment method is used most frequently? |
| Total Sales by Mobile Model — Bar Chart | Product ranking | Which models generate the most sales? |
| Total Sales by Day Name | Weekly pattern | Which days generate higher sales? |
| Brand Performance Table | Brand-level comparison | Which brands contribute most to sales? |

### Rating Classification

- **Good:** rating 4–5
- **Average:** rating 3
- **Poor:** rating 1–2

---

# 5. Dashboard 2 — MTD Report

### Purpose

The MTD dashboard focuses on **Month-to-Date performance** for a selected year. The shown report is filtered to **2022**.

### KPI Snapshot — 2022

| KPI | Value |
|---|---:|
| Total Sales | ₹261.99M |
| Total Quantity | 6.43K |
| Transactions | 1.28K |
| Average Price | ₹40.51K |

### Main Visual — MTD by Year, Quarter, Month and Day

The line chart shows cumulative sales progression inside each month.

**Why MTD is useful:** It tracks how sales accumulate during a month instead of looking only at the final monthly total.

**Business questions:**
- How quickly are sales accumulating during each month?
- Which months reach higher sales levels?
- Are some months consistently stronger or weaker?
- How is current monthly progress developing?

### Filters

- Mobile Model
- Payment Method
- Year
- Month

---

# 6. Dashboard 3 — Same Period Last Year

### Purpose

Compares the selected year's sales with the **same period in the previous year**. The shown dashboard compares **2023 vs 2022**.

### KPI Snapshot — 2023

| KPI | Value |
|---|---:|
| Total Sales | ₹253.31M |
| Total Quantity | 6.36K |
| Transactions | 1.29K |
| Average Price | ₹39.73K |

### Year-over-Year Comparison

2023 sales: **₹253.31M**  
2022 sales: **₹261.99M**

Difference: **approximately −₹8.68M (-3.31%)**

The dashboard uses:
- Year-level comparison
- Quarter-level comparison
- Month-level comparison

### Business Questions

- Which quarter changed most compared with the previous year?
- Which quarters performed close to the previous year?
- Which months improved?
- Which months declined?
- Are year-over-year changes concentrated in specific months?

---

# 7. Dataset-Based Observations

### Brand Sales

| Brand | Sales |
|---|---:|
| Apple | ₹161.62M |
| Samsung | ₹160.04M |
| OnePlus | ₹153.72M |
| Vivo | ₹150.08M |
| Xiaomi | ₹143.75M |

### Payment Methods

UPI represents approximately **26.36% of transactions**, followed by Debit Card, Credit Card and Cash.

### Top Sales City

**Delhi** contributes approximately **₹203.88M** in sales in the dataset.

### Top Mobile Models by Sales

| Mobile Model | Sales |
|---|---:|
| iPhone SE | ₹59.57M |
| OnePlus Nord | ₹57.89M |
| Galaxy Note 20 | ₹56.01M |
| Vivo Y51 | ₹54.84M |
| Galaxy S21 | ₹53.27M |

---

# 8. Important Business Questions

### Sales Performance
1. What is total sales?
2. How many units have been sold?
3. How many transactions have occurred?
4. What is the average selling price?
5. How are sales changing month by month?

### Product Analysis
6. Which brand generates the highest sales?
7. Which mobile model generates the highest sales?
8. Which models sell the highest quantity?
9. How does brand performance vary over time?

### Geographic Analysis
10. Which city generates the highest sales?
11. How are sales distributed geographically?
12. Which cities have comparatively lower sales?

### Customer Analysis
13. What is the customer rating distribution?
14. What percentage of ratings are Good, Average and Poor?
15. Does customer rating vary across products or locations?

### Payment Analysis
16. Which payment method is most frequently used?
17. How does transaction volume differ by payment method?

### Time Intelligence
18. What is the MTD sales trend?
19. How does the current year compare with the previous year?
20. Which months or quarters show the largest year-over-year change?

---

# 9. Power BI Skills Demonstrated

- Excel data import
- Data cleaning and preparation
- Power Query
- Data modeling
- DAX measures
- KPI cards
- Slicers
- Interactive filtering
- Time-intelligence analysis
- MTD analysis
- Same Period Last Year analysis
- Year-over-Year comparison
- Geographic visualization
- Trend analysis
- Business-focused dashboard design

---

# 10. Project Outcome

The project converts raw mobile-sales transaction data into an interactive business intelligence solution.

**Dashboard 1 → Overall Sales Performance**  
**Dashboard 2 → MTD Performance Tracking**  
**Dashboard 3 → Year-over-Year / Same Period Last Year Analysis**

Together, the dashboards move from **high-level KPIs → detailed trends → comparative performance analysis**.

---

# 11. Interview Explanation

### Tell me about your Power BI project.

> I created a Mobile Sales Analytics dashboard in Power BI using an Excel transaction dataset containing 3,835 transactions. I built three dashboards: an overall sales dashboard, an MTD report, and a Same Period Last Year analysis dashboard. I used Power Query for data preparation and DAX for KPI and time-based calculations. The dashboards track total sales, quantity, transactions and average price, along with brand, mobile model, city, payment method, customer ratings and monthly trends. I also implemented MTD and year-over-year comparisons to analyze sales performance over time.

### Why did you create three dashboards?

> Each dashboard addresses a different business requirement. The first provides an overall performance view, the second focuses on month-to-date tracking, and the third compares the selected period with the corresponding period of the previous year.

### Why did you use MTD?

> MTD helps track how sales are accumulating within the month and allows management to monitor progress before the month is completed.

### Why did you use Same Period Last Year?

> It provides a like-for-like comparison with the previous year's corresponding period and helps identify changes in performance over time.

---

# 12. Suggested GitHub Repository Structure

```text
Mobile-Sales-PowerBI/
│
├── README.md
├── Dataset/
│   └── Mobile-Sales-Data.xlsx
├── PowerBI/
│   └── Mobile-Sales-Dashboard.pbix
├── Screenshots/
│   ├── Dashboard.png
│   ├── MTD-Report.png
│   └── Same-Period-Last-Year.png
└── Documentation/
    └── Project-Documentation.md
```

## Project Summary

**Mobile Sales Analytics** demonstrates how Power BI can transform transaction-level data into an interactive reporting solution. The project covers sales KPIs, product performance, geographic analysis, customer ratings, payment methods and time-intelligence reporting through overall performance, MTD tracking and same-period-last-year analysis.
