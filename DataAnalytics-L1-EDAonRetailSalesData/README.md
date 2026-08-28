# Level 1
# Task 1 · EDA on Retail Sales Data

## Objective
Perform a thorough Exploratory Data Analysis on a retail sales dataset to uncover patterns, customer behaviour trends, and actionable business insights.

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook

## Dataset
`retail_sales_dataset.csv` — transactional retail sales data including customer demographics, product categories, quantities, and revenue.

## What This Notebook Covers
- Data loading and initial inspection (shape, dtypes, null checks)
- Descriptive statistics: mean, median, mode, standard deviation for numerical columns
- Time series analysis: monthly and quarterly sales trends via line charts
- Customer demographics analysis: gender breakdown and age group distribution
- Product analysis: top 10 product categories by quantity sold, and revenue by category
- Correlation heatmap across numerical variables
- Additional insight: order value variation across age groups and category preferences

## Key Findings
- Sales fluctuate seasonally, with sharp peaks in high-demand months.
- Customer base is nearly gender-balanced, with slightly more female customers.
- Clothing leads in quantity sold; Electronics generates the highest revenue.
- Price per Unit shows the strongest positive correlation with Total Amount.

## Business Recommendations
1. Shift marketing focus toward the 18–25 age group.
2. Prioritize inventory and promotions around Electronics and Clothing categories.
3. Plan targeted seasonal campaigns around identified peak months.

## How to Run
1. Open `EDAonRetailSalesData.ipynb` in Jupyter Notebook.
2. Ensure `retail_sales_dataset.csv` is in the same directory.
3. Run all cells sequentially.