# Bike Sharing Demand Analysis

## Project Overview
          This project analyzes bike-sharing rental data to understand customer behaviour, hourly demand patterns, seasonal trends, and the relationship between weather conditions and bike rentals.

          The analysis uses Python and data analytics libraries to generate business insights and visualizations that can support operational and marketing decisions.

## Business Objectives
          - Identify peak rental hours.
          - Compare rental demand across weekdays.
          - Analyze seasonal rental patterns.
          - Understand how weather conditions relate to rental demand.
          - Compare casual and registered customer behaviour.
          - Explore correlations between weather variables and rental counts.

## Tools and Technologies
          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook

## Project Workflow

### 1. Data Inspection
          - Checked dataset dimensions and data types.
          - Reviewed descriptive statistics.
          - Checked missing values and duplicate records.
          - Verified rental count consistency.
          - Confirmed unique record IDs.

### 2. Data Cleaning and Feature Engineering
          - Converted the date column to datetime.
          - Extracted day name, month name, and year.
          - Created a weekend indicator.
          - Added readable season and weather labels.
          - Categorized hours into demand periods.
          - Classified working and non-working days.

### 3. Exploratory Data Analysis
          - Analyzed hourly rental demand.
          - Compared average rentals by weekday and season.
          - Examined rental demand across weather conditions.
          - Calculated casual and registered customer contributions.
          - Studied customer behaviour by hour.
          - Used correlation analysis to explore numerical relationships.

### Customer Behaviour
          Registered customers account for approximately 81.17% of total rentals, while casual customers account for approximately 18.83%.

          Registered rentals show prominent morning and evening peaks. Casual rentals are comparatively more spread across the day.

### Weather and Demand
          Average rental demand is highest in clear or partly cloudy conditions and lower in adverse weather categories.

## Business Recommendations
          1. Ensure sufficient bike availability during morning and evening peak hours.
          2. Consider targeted promotions to convert casual customers into registered users.
          3. Plan seasonal fleet availability based on observed demand.
          4. Consider weather conditions when planning bike distribution and operations.
          5. Use hourly demand patterns to support staffing and maintenance scheduling.

## Conclusion
          The analysis identifies clear hourly demand peaks, seasonal differences, and a strong contribution from registered customers. These findings can help a bike-sharing business improve resource allocation, customer engagement, and operational planning.
