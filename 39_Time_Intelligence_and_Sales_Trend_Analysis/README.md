# Day 39: Time Intelligence and Sales Trend Analysis

## 1. Project Overview

          This project analyzes the Sample Superstore dataset to understand sales performance over time.

          The main objective is to apply time intelligence concepts using Python and Pandas, including Monthly Sales, Month-to-Date (MTD), Quarter-to-Date (QTD), Year-to-Date (YTD), and Year-over-Year (YoY) growth.

## 2. Business Objectives

          - Analyze monthly sales trends.
          - Compare quarterly and yearly sales performance.
          - Calculate MTD, QTD and YTD sales.
          - Compare current-year sales with the previous year.
          - Calculate monthly and annual YoY growth.
          - Identify the strongest sales months and quarters.
          - Present findings through visualizations.

## 4. Tools and Technologies

          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook

## 5. Project Workflow

### Commit 1: Dataset Inspection

          - Loaded the Superstore CSV dataset.
          - Inspected dataset shape, columns and data types.
          - Checked missing values and duplicate records.
          - Examined sales statistics and date values.
          - Identified mixed date separators.

### Commit 2: Date Cleaning and Feature Engineering

          - Removed the exact duplicate record.
          - Standardized date separators.
          - Converted Order Date into datetime format.
          - Extracted year, month, month number, quarter and day name.
          - Created a separate continuous date dimension.
          - Added weekend indicators.

### Commit 3: Time Intelligence Calculations

          - Calculated daily sales.
          - Calculated MTD sales.
          - Calculated QTD sales.
          - Calculated YTD sales.
          - Created monthly sales summaries.
          - Calculated previous-year monthly sales.
          - Calculated monthly YoY growth.
          - Validated daily and monthly sales totals.

### Commit 4: Dashboard and Business Insights

          - Visualized monthly sales trends.
          - Compared quarterly sales across years.
          - Compared annual sales performance.
          - Visualized monthly YoY growth.
          - Calculated latest MTD, QTD and YTD KPIs.
          - Identified the strongest sales month, quarter and year.

## 6. Key Business Findings

          | Metric | Result |
          |---|---:|
          | Overall Sales | $2,296,919.49 |
          | Average Monthly Sales | $47,852.49 |
          | Highest Sales Month | November 2017 |
          | November 2017 Sales | $118,447.83 |
          | Best Performing Quarter | 2017 Q4 |
          | Best Performing Year | 2017 |
          | 2015 Annual YoY Growth | -2.78% |
          | 2016 Annual YoY Growth | +29.47% |
          | 2017 Annual YoY Growth | +20.36% |

## 7. Business Recommendations

          1. Investigate the factors behind the strong November sales performance.
          2. Review the sales decline in 2015 to identify possible business issues.
          3. Study the factors that contributed to sales growth in 2016 and 2017.
          4. Monitor quarterly performance to identify seasonal revenue patterns.
          5. Use MTD, QTD and YTD metrics for regular management reporting.
          6. Compare current sales with corresponding previous-year periods to monitor growth.

## 8. Important Analytical Notes

          - MTD, QTD and YTD are cumulative metrics calculated using the available transaction dates.
          - The first 12 monthly records have no previous-year monthly comparison.
          - 2017 data ends on December 30, 2017, so annual sales represent the available dataset records.
          - YoY growth measures percentage change, not absolute sales difference.

## 9. Conclusion

          This project demonstrates how time intelligence can support retail business analysis.

          Using Pandas, NumPy, Matplotlib and Seaborn, the analysis transforms transaction-level data into daily, monthly, quarterly and yearly performance metrics.

          The findings highlight sales growth patterns, important revenue periods and useful indicators for management decision-making.


