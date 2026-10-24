# Day 35 — Advanced Seaborn Visualization

## Overview
          Practiced advanced data visualization with Seaborn to analyze relationships, distributions, and business performance across product categories and regions.

## Topics Covered
          - `sns.pairplot()` — visualize pairwise relationships between numerical variables.
          - `sns.jointplot()` — examine the relationship between two variables alongside their individual distributions.
          - `sns.relplot()` — create relational plots with category-based panels.
          - `hue` — distinguish groups using colors.
          - `col` — split visualizations into separate panels.
          - `kind` — select the type of relational plot.
          - Profit margin analysis using Pandas.

## Dataset
          A sample retail sales dataset containing:
          - Category
          - Region
          - Sales
          - Profit
          - Customers
          - Discount

## Practical Work
          1. Visualized pairwise relationships among Sales, Profit, Customers, and Discount.
          2. Used joint plots to examine Sales and Profit relationships.
          3. Created relational plots comparing categories and regions.
          4. Calculated average profit margin by category.
          5. Ranked categories by average profit margin.

## Key Business Insights
          - Furniture recorded the highest average Sales and Profit Margin in the analyzed sample.
          - Food recorded the lowest average Profit Margin.
          - Category-based panels made differences in performance across product categories easier to compare.
          - Visualizations support further investigation, but the sample alone does not establish why profitability differs.

## Final Analysis
          Average profit margin was calculated as:

          `Profit Margin (%) = Profit / Sales × 100`

          The average margin was grouped by category and sorted in descending order.

## Tools and Libraries
          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook

## Learning Outcome
          Practiced advanced Seaborn visualizations and combined visual analysis with Pandas-based business KPIs to interpret category performance.
