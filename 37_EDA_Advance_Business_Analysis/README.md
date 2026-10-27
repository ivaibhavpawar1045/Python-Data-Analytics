# Day 37 — Complete Exploratory Data Analysis (EDA)

## Overview
          Completed a guided Exploratory Data Analysis (EDA) session using the **Online Retail II dataset**. The focus was on understanding transaction sales distributions, exploring relationships between variables, and interpreting patterns relevant to retail business decisions.

## Topics Covered

### 1. Univariate Analysis
          Studied one numerical variable at a time using descriptive statistics and visualizations.

### 2. Distribution Visualization
          Created histograms to inspect the full sales distribution and zoom into the central transaction range. Used a box plot to identify potential outliers.

          **Key learning:**
          - Histograms show frequencies across numerical intervals.
          - Box plots summarize distribution spread and flag potential outliers.
          - Axis limits change the displayed range but do not remove records.
          - Filtering for visualization should not be confused with permanent data cleaning.

### 3. Bivariate Analysis
          Explored the relationship between `Quantity` and `Sales` using a scatter plot.

          **Business interpretation:** Extreme quantities and transaction values can compress the central pattern. Negative quantities and sales warrant investigation because they may represent returns or adjustments.

          **Technique used:** Seaborn `scatterplot()`.

### 4. Multivariate Analysis
          Created a calculated sales measure:

          ```python
          sales_data_clean["Calculated_Sales"] = (
          sales_data_clean["Quantity"]
          * sales_data_clean["Price"]
          )
          ```

          Explored the relationship between quantity, calculated sales, and price using a scatter plot with color encoding.

## Business Skills Developed
          - Interpreting descriptive statistics.
          - Comparing means and medians.
          - Investigating extreme transaction values.
          - Exploring relationships between retail variables.
          - Translating charts into preliminary business insights.
          - Recognizing the limitations of filtered visualizations.

## Key Takeaways
          1. EDA helps identify patterns and potential data-quality issues before deeper analysis.
          2. Extreme values can distort summary statistics and visualizations.
          3. Negative sales values require contextual investigation.
          4. Correlation or visual association does not establish causation.
          5. Business recommendations should be based on verified findings and appropriate data context.
