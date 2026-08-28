# Level 1
# Task 3 · Cleaning Data

## Objective
Demonstrate professional-level data cleaning skills by taking a deliberately messy dataset and systematically transforming it into a clean, analysis-ready dataset, with every decision documented.

## Tech Stack
Python, pandas, numpy, Jupyter Notebook

## Dataset
- Input: `dirty_cafe_sales.csv` — deliberately messy cafe sales data
- Output: `cleaned_cafe_sales.csv` — cleaned, analysis-ready version

## What This Notebook Covers
- Initial data quality inspection (nulls, dtypes, structure)
- Duplicate row removal
- Standardizing missing-value placeholders and text formatting (Item, Payment Method, Location)
- Standardizing transaction date formats
- Missing data imputation and type conversion for:
  - Price Per Unit
  - Quantity
  - Total Spent (recalculated where needed)
  - Item
  - Payment Method & Location
- Enforcing strict, correct data types across all columns
- Exporting the final cleaned dataset to CSV

## Key Outcome
A fully cleaned `cleaned_cafe_sales.csv` file with consistent formatting, corrected data types, and imputed missing values — ready for downstream analysis.

## How to Run
1. Open `Cleaning_Data.ipynb` in Jupyter Notebook.
2. Ensure `dirty_cafe_sales.csv` is in the same directory.
3. Run all cells sequentially.
4. The cleaned output is saved as `cleaned_cafe_sales.csv`.