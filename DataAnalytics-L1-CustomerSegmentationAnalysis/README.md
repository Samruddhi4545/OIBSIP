# Level 1
# Task 2 · Customer Segmentation Analysis

## Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour, enabling targeted marketing strategies.

## Tech Stack
Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Jupyter Notebook

## Dataset
`E-Commerce.csv` — order-level e-commerce transaction data.

## What This Notebook Covers
- Data loading, inspection, and duplicate checks
- Filtering to completed orders only
- RFM (Recency, Frequency, Monetary) feature engineering via aggregation
- Feature standardization using `StandardScaler`
- Elbow Method to determine the optimal number of clusters (K)
- K-Means clustering and cluster profiling
- Visualization: scatter plots of clusters and a bar chart of customer counts per cluster

## Key Findings
- Customers were segmented into distinct behavioural groups based on RFM metrics.
- Cluster 3 stood out as the only repeat-customer segment, containing just 256 customers — a small but high-value group.

## Business Recommendations
- Design retention campaigns specifically targeting the repeat-customer cluster.
- Investigate why other clusters show low repeat-purchase behaviour and test re-engagement offers.

## How to Run
1. Open `Customer_Segmentation_Analysis.ipynb` in Jupyter Notebook.
2. Ensure `E-Commerce.csv` is in the same directory.
3. Run all cells sequentially.