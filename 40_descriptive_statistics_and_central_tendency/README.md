# Day 40: Descriptive Statistics and Statistical Distribution Analysis

## 1. Project Overview

          This project applies descriptive statistics to the Sample Superstore dataset to understand sales, quantity and profit behaviour.

          The objective is to summarize numerical data, measure variability, identify distribution patterns and detect potential outliers using Python.

## 2. Business Objectives

          - Calculate Mean, Median and Mode.
          - Understand Range, Variance and Standard Deviation.
          - Calculate Quartiles and Interquartile Range (IQR).
          - Analyze distribution skewness.
          - Identify potential outliers using the IQR method.
          - Interpret statistical findings from a business perspective.

## 3. Dataset Information

**Dataset:** Sample - Superstore.csv

          - Original records: 9,994
          - Records after duplicate removal: 9,993
          - Columns: 14
          - Missing values: 0
          - Duplicate records after cleaning: 0

## 4. Tools and Technologies

          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook

## 5. Project Workflow

### Commit 1: Dataset Inspection

          - Loaded the Superstore dataset.
          - Inspected dataset dimensions and data types.
          - Generated numerical and categorical summaries.
          - Checked missing values and duplicate records.
          - Calculated basic business metrics.

### Commit 2: Measures of Central Tendency

          - Removed the exact duplicate record.
          - Calculated Mean, Median and Mode for Sales, Quantity and Profit.
          - Compared mean and median.
          - Interpreted typical customer purchasing behaviour.

### Commit 3: Measures of Dispersion and Distribution

          - Calculated Range, Variance and Standard Deviation.
          - Calculated quartiles and IQR.
          - Measured distribution skewness.
          - Identified potential outliers using IQR boundaries.
          - Created histograms and boxplots.

### Commit 4: Final Business Insights

          - Combined central tendency and dispersion results.
          - Calculated outlier percentages.
          - Interpreted statistical findings.
          - Validated final dataset quality.
          - Documented business observations.

## 6. Central Tendency Results

          | Variable | Mean | Median | Mode |
          |---|---:|---:|---:|
          | Sales | 229.85 | 54.48 | 12.96 |
          | Quantity | 3.79 | 3.00 | 3.00 |
          | Profit | 28.66 | 8.67 | 0.00 |

## 7. Statistical Dispersion Results

          | Variable | Range | Variance | Standard Deviation | IQR | Skewness |
          |---|---:|---:|---:|---:|---:|
          | Sales | 22,638.04 | 388,473.06 | 623.28 | 192.66 | 12.97 |
          | Quantity | 13.00 | 4.95 | 2.23 | 3.00 | 1.28 |
          | Profit | 14,999.95 | 54,883.12 | 234.27 | 27.63 | 7.56 |

## 8. Outlier Analysis

          Outliers were identified using the Interquartile Range method.

          | Variable | Outlier Count | Outlier Percentage |
          |---|---:|---:|
          | Sales | 1,167 | 11.68% |
          | Quantity | 170 | 1.70% |
          | Profit | 1,881 | 18.82% |

          These are statistical flags, not automatically incorrect transactions. Further investigation is required before deciding whether any record should be excluded.

## 9. Final Business Findings

          1. Average sales are higher than median sales, indicating that large transactions influence the average.
          2. The median order quantity is 3 units, which represents the middle observation.
          3. Average profit is higher than median profit, suggesting variation in transaction profitability.
          4. Sales and Profit distributions show strong positive skewness.
          5. Profit has the highest outlier percentage at 18.82%.
          6. Sales show substantial variation across individual transactions.

## 10. Business Recommendations

          - Use median sales alongside average sales when reporting typical transaction value.
          - Investigate unusually high-value sales transactions.
          - Review loss-making and unusually profitable transactions.
          - Examine profit outliers to identify pricing, discount or cost-related patterns.
          - Monitor purchase quantities to understand common customer order sizes.
          - Avoid removing statistical outliers without validating their business context.

## 11. Final Dataset Validation

          | Validation | Result |
          |---|---:|
          | Final records | 9,993 |
          | Columns | 14 |
          | Missing values | 0 |
          | Duplicate records | 0 |
          | Total Sales | 2,296,919.49 |
          | Total Profit | 286,409.08 |

## 12. Conclusion

          This project demonstrates how descriptive statistics help analysts understand the central values, variability and distribution of business data.

          Using Pandas, NumPy, Matplotlib and Seaborn, the analysis identifies typical sales behaviour, measures transaction variability and detects potential outliers.

          These statistical techniques provide a foundation for more advanced business analytics, statistical inference and machine learning.

