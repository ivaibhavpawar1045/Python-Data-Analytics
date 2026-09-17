# Day 23 — Advanced Filtering & Conditional Business Analysis

## 📌 Overview

          This project is part of my Python for Data Analytics learning journey.

          Day 23 focuses on applying advanced Pandas filtering, business-rule classification, categorical analysis, and customer segmentation using the **DataCo Supply Chain Dataset**.

          The objective was to move beyond basic data manipulation and practice how an analyst converts real-world business questions into structured data analysis.

## 🎯 Objectives

          - Apply single and multiple-condition filtering
          - Use Boolean operators with Pandas
          - Filter multiple categories using `isin()`
          - Filter numerical ranges using `between()`
          - Create business classification columns using `np.select()`
          - Analyze profitability categories
          - Build Crosstab business matrices
          - Investigate high-value loss-making transactions
          - Analyze discount patterns
          - Perform customer-level aggregation
          - Calculate customer revenue contribution
          - Identify high-value customers using a data-driven percentile threshold

## 🗂️ Dataset

          **Dataset:** DataCo Supply Chain Dataset

          **Shape:**
          - Rows: 180,519
          - Columns: 31

          The dataset contains information related to:

          - Customers
          - Products
          - Sales
          - Profit
          - Discounts
          - Customer Segments
          - Order Regions
          - Delivery Status
          - Order Status
          - Shipping Information

## 📌 Key Takeaways -

# Technical
         - Pandas Boolean filtering is essential for real-world analytics.
         - isin() simplifies multi-category filtering.
         - between() makes range-based filtering readable.
         - np.select() is useful for creating business classification columns.
         - pd.crosstab() can reveal relationships between categorical business variables.
         - Percentile-based segmentation can create data-driven customer groups.

# Business
         - High-value transactions can still generate losses.
         - Discount patterns should be investigated alongside profitability rather than interpreted in isolation.
         - Customer-level aggregation provides a different perspective from transaction-level analysis.
         - Revenue contribution helps understand customer concentration.
         - Business conclusions should be supported by evidence rather than assumptions.