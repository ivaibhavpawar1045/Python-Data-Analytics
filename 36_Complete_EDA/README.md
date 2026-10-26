# Day 36 — Complete Exploratory Data Analysis (EDA)

## Overview
          Performed an end-to-end exploratory data analysis workflow on the Online Retail II dataset using Pandas, NumPy, Matplotlib, and Seaborn.

## 1. Data Inspection
          - Inspected dataset shape, column names, data types, and descriptive statistics.
          - Examined numerical ranges and missing values.
          - Identified unusual quantities and prices for further investigation.

## 2. Data Quality and Cleaning
          - Identified 6,865 duplicate rows.
          - Identified 2,928 missing product descriptions.
          - Removed duplicate rows and records missing descriptions for product-level analysis.
          - Preserved missing Customer ID values.
          - Retained cancellation and return transactions for business analysis.

## 3. Feature Engineering
          Created a transaction-level Sales column:

          `Sales = Quantity × Price`

          Created an Is_Cancelled indicator using invoice identifiers beginning with C.

## 4. Statistical Analysis
          - Examined mean, median, standard deviation, minimum, maximum, and selected percentiles.
          - Observed a median transaction sales value of 10.08.
          - Observed a 95th-percentile sales value of 60.00.
          - Identified extreme values requiring careful interpretation.

## 5. Visualization
          - Created a histogram of transaction sales.
          - Investigated the central distribution using a restricted visualization range.
          - Observed a strongly right-skewed distribution with a concentration of small transaction values.

## 6. Business Interpretation
          - Transaction values vary substantially.
          - Negative transaction values may reflect returns or cancellations.
          - Sales analysis should distinguish transaction-level net sales from other revenue definitions.
          - Missing customer identifiers limit customer-level analysis but do not prevent all sales analysis.

## Tools and Libraries
          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook


