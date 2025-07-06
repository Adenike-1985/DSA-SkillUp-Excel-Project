# 📘 Table of Contents

- [📌 Project Topic](#-project-topic)
- [📖 Project Description](#-project-description)
- [📂 Data Sources](#-data-sources)
- [🧰 Tools Utilized](#-tools-utilized)
- [📊 Exploratory Data Summary](#-exploratory-data-summary)
- [🔧 Project Methodology](#-project-methodology)
- [📈 Key Insights and Strategic Analysis](#-key-insights-and-strategic-analysis)
- [✅ Strategic Recommendations](#-strategic-recommendations)

---

# 📌 Project Topic

*Analyzing Sales, Customer Behavior, and Logistics at Kultra Mega Stores (KMS)*

---

## 📖 Project Description

As part of the DSA Data Analysis Capstone Project, this analysis was conducted on historical order records of Kultra Mega Stores (KMS), a Lagos-based office supplies and furniture retailer. The purpose of the project was to deliver actionable insights that could help optimize business performance in areas such as customer segmentation, logistics, sales strategy, and return management. The analysis was driven by structured SQL queries and supported by dynamic dashboards built in Power BI.

---

## 📂 Data Sources

The project used two primary data files:

- KMS Sql Case Study.csv — seated on my LMS Canvas which contains comprehensive transaction details (orders, sales, profits, shipping) between 2009–2012.
- Order Status.csv — includes only returned orders, allowing for analysis of product return behavior.

---

## 🧰 Tools Utilized

| Function               | Tool                    |
|------------------------|-------------------------|
| Data Preparation       | Microsoft Excel         |
| Database and Querying  | Microsoft SQL Server    |

---

## 📊 Exploratory Data Summary

The analysis addressed the following business-critical questions:

- Which product categories and regions had the highest and lowest sales?
- Who are the top-performing and underperforming customers?
- How do different shipping methods align with order priorities?
- What customer segments are associated with the most product returns?

Each of these questions was explored using SQL

---

## 🔧 Project Methodology

1. *Excel Data Cleaning*
   - Replaced invalid or unspecified values
   - Formatted dates to ISO standard (yyyy-mm-dd)
   - Reviewed and corrected nulls and duplicates

2. *SQL Server Integration*
   - Imported both datasets and created necessary joins
   - Built SQL views combining customer orders and return statuses

3. *Query Execution*
   - Used SQL to perform aggregation, filtering, and segmentation
   - Applied functions like TOP, JOIN, and GROUP BY,e.t.c to extract answers

---

## 📈 Key Insights and Strategic Analysis

### 🔹 Customer Behavior (Q4)
- Bottom 10 customers are primarily in the *Consumer* and *Home Office* segments.
- Their purchases focus on *Furniture* and *Office Supplies* — low revenue per transaction.

### 🔹 Shipping Effectiveness (Q11)
- High-priority orders (e.g., Critical) often used *Delivery Truck* instead of *Express Air*.
- Meanwhile, many *Low-priority orders* were delivered using costly *Express Air* shipping.

### 🔹 Product Returns (Q10)
- Product returns are concentrated among *Consumer customers*.
- Categories with most returns include *Furniture* and *Office Supplies*.

  ### 🔹 [Click Here for the Queries](PROJECT DSA)

---

## ✅ Strategic Recommendations

### 1. Boosting Revenue from Low-Spending Customers
- Offer targeted incentives, loyalty programs, and volume-based discounts.
- Encourage bulk purchases with value bundles (e.g., desk + chair + organizer).
- Deploy personalized email outreach and follow-up by sales representatives.

### 2. Shipping Policy Enforcement
- Design and enforce a *priority-based shipping matrix*.
- Set up system rules or training to auto-assign ship modes based on urgency.
- Avoid misaligned shipping choices to cut logistics costs.

### 3. Return Prevention Strategy
- Invest in customer education and pre-sale clarity (product info, usage).
- Improve packaging and delivery experience.
- Analyze product defects or supplier issues where return volume is high.

---
