# Day 25 — Regional Performance Segmentation & Comparative Business Analysis

## 📌 Overview

          Day 25 is part of my **Python for Data Analytics** learning journey.

          This session focused on taking regional business analysis to the next level by combining multiple KPIs and creating a structured **performance segmentation framework**.

          Instead of analyzing Sales, Profit, Shipping, and Delivery Risk independently, this session combined them to answer more meaningful business questions such as:

          - Which regions generate the most revenue?
          - Which regions have the strongest profit margins?
          - Which regions generate high revenue but relatively lower margins?
          - Which regions combine high revenue with high margins?
          - How does delivery risk vary across performance segments?
          - Which regions may require additional operational attention?

# 🎯 Learning Objectives

          - Building multi-KPI summary tables
          - Using `groupby()` with multiple aggregations
          - Creating calculated business metrics
          - Calculating Profit Margin %
          - Calculating Late Risk %
          - Using median-based business benchmarks
          - Creating multi-condition classifications
          - Using `np.select()` for segmentation
          - Comparing revenue against profitability
          - Performing cross-segment analysis
          - Using `idxmax()` and `idxmin()`
          - Filtering based on multiple business conditions
          - Comparing operational KPIs across business segments
          - Translating Pandas output into business insights
          - Creating an analyst-style opportunity analysis

# 💼 Final Business Insights
          - Western Europe generated the highest regional sales at approximately 5.89M.
          - Southern Africa recorded the highest regional profit margin at approximately 13.51%.
          - The highest-sales region and highest-margin region were different.
          - High Revenue / High Margin contained 5 regions.
          - High Revenue / Low Margin contained 7 regions.
          - Low Revenue / High Margin contained 7 regions.
          - Low Revenue / Low Margin contained 4 regions.
          - The High Revenue / High Margin segment had average sales of approximately 2.80M and average margin of 11.16%.
          - The High Revenue / Low Margin segment had average sales of approximately 2.33M and average margin of 10.42%.
          - The Low Revenue / High Margin segment had the highest average margin at approximately 11.89%.
          - The Low Revenue / Low Margin segment had the highest average late-risk rate at approximately 55.86%.
          - Within the High Revenue / Low Margin segment, South Asia had the highest late-risk rate at approximately 56.27%.
          - Within the High Revenue / Low Margin segment, Eastern Asia had the lowest profit margin at approximately 9.91%.
          - The analysis demonstrates why business performance should be evaluated using multiple KPIs rather than revenue alone.