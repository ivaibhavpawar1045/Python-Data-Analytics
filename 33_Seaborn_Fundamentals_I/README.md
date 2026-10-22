# Day 33 — Seaborn Data Visualization

## 📌 Overview
          - Day 33 focused on using Seaborn to create statistical visualizations and analyze business performance by product category. 
          - Matplotlib was used to configure figures, titles, labels, and multiple charts.

## 🎯 Learning Objectives
          - Create statistical charts using Seaborn.
          - Compare average sales and profit margins across categories.
          - Understand category frequencies and numerical distributions.
          - Visualize relationships between sales and profit.
          - Build a dashboard using multiple charts.

## 🛠️ Technologies Used
          - Python
          - Pandas
          - NumPy
          - Matplotlib
          - Seaborn
          - Jupyter Notebook

### Key Findings
          - **Furniture** recorded the highest average sales at ₹20,000.
          - **Furniture** also recorded the highest average profit margin at approximately 19.12%.
          - Each category contained two observations.
          - The scatter plot showed sales and profit increasing together in this illustrative dataset.
          - The box plot helped compare sales distributions across categories.

## 💡 Business Interpretation
          Furniture is the strongest category in this sample for both average sales and average profit margin. However, the dataset is small and illustrative; these findings should be validated using actual business data before making operational or investment decisions.

## 🧠 Key Takeaways
          - `barplot()` compares category-level averages by default.
          - `countplot()` displays observation counts.
          - `histplot()` shows numerical distributions.
          - `scatterplot()` explores relationships between variables.
          - `boxplot()` compares distributions and identifies potential outliers.
          - `plt.subplots()` enables multiple charts in one figure.
          - `ax=` specifies the plotting area used by a Seaborn chart.
