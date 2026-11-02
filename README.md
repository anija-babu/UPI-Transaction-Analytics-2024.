# UPI Transaction Analytics 2024

## 📌 Project Overview

The **UPI Transaction Analytics 2024** project is an interactive Power BI dashboard designed to analyze UPI transaction data and identify meaningful insights into transaction trends, customer behavior, and banking activity.

The dashboard transforms raw transaction data into interactive visualizations and key performance indicators (KPIs), helping users understand transaction performance, payment patterns, and bank activity.

## 🎯 Project Objectives

- Analyze transaction volume and transaction amounts.
- Monitor successful and failed transactions.
- Identify customer transaction patterns across age groups, genders, and locations.
- Analyze transaction activity across sending and receiving banks.
- Explore merchant categories, payment methods, and device usage.
- Present key business insights through an interactive dashboard.

## 🛠️ Tools and Technologies

- **Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** – Measures, KPIs, and analytical calculations.
- **Data Modeling** – Relationships between the transaction fact table and date dimension.
- **CSV / Excel** – Data source and preparation.

## 📊 Dashboard Pages

### 1. Transaction Overview

Provides a high-level overview of UPI transaction performance.

**Key Analyses:**
- Total transaction amount and transaction count.
- Monthly transaction trends.
- Transaction type distribution.
- Successful and failed transaction analysis.
- City-wise transaction activity.
- Month-over-month transaction growth.

**Purpose:** To monitor overall transaction performance and identify trends and changes in transaction activity.

### 2. Customer Insights

Explores customer transaction behavior across different demographic and usage categories.

**Key Analyses:**
- Customer age-group analysis.
- Gender-wise transaction activity.
- State-wise transaction amount and rankings.
- Device usage patterns.
- Merchant category spending distribution.

**Purpose:** To understand customer transaction patterns and identify the customer segments and locations contributing to transaction activity.

### 3. Bank Insights

Focuses on transaction activity across banks, merchants, and payment methods.

**Key Analyses:**
- Sending and receiving bank activity.
- Top receiving banks by transaction count.
- Net bank flow analysis.
- Most-used payment mode.
- Merchant category transaction distribution.

**Purpose:** To compare banking activity and understand how transactions are distributed across banks, merchants, and payment modes.

## 📐 DAX and Key Measures

DAX measures are used to calculate important metrics and support interactive analysis.

**Examples include:**

- **Total Transaction Amount** – Calculates the total transaction value.
- **Total Transaction Count** – Counts distinct transactions.
- **Successful Transactions** – Calculates the number of successful transactions.
- **Transaction Success Rate** – Measures the percentage of successful transactions.
- **Previous Month Transaction Amount** – Calculates the previous month's transaction value.
- **Month-over-Month Growth** – Measures changes in transaction amount compared with the previous month.
- **Top State Ranking** – Ranks states based on transaction amount.
- **Most Active Age Group** – Identifies the age group with the highest transaction activity.

## 🗂️ Data Model

The project uses a simple data model consisting of two tables:

- **UPI Transactions Fact Table:** Contains transaction details, amounts, dates, customer information, bank details, merchants, payment methods, and transaction status.
- **Date Dimension Table:** Supports date-based analysis, including year, month, and day.

A relationship connects the date dimension to the transaction fact table, enabling time-based filtering and analysis.

## ✨ Dashboard Features

- Interactive slicers for filtering transaction data.
- KPI cards for key performance indicators.
- Line charts for monthly trends.
- Bar charts for comparisons and rankings.
- Donut charts for categorical distributions.
- Treemaps for merchant category analysis.
- Conditional formatting and visual highlights.
- Interactive navigation across dashboard pages.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Cleaning and preparing transaction data using Power Query.
- Building a date dimension and establishing data relationships.
- Creating calculated measures using DAX.
- Applying ranking and time-intelligence calculations.
- Designing interactive Power BI dashboards.
- Translating transaction data into meaningful business insights.

## 📝 Conclusion

The **UPI Transaction Analytics 2024** project demonstrates how Power BI can be used to transform transaction data into an interactive analytical solution. By combining data modeling, DAX measures, and visual storytelling, the dashboard provides a structured view of transaction performance, customer behavior, and banking activity.

---

**Project Type:** Data Analytics | Business Intelligence

**Tools:** Power BI, Power Query, DAX

**Dataset Period:** 2024
