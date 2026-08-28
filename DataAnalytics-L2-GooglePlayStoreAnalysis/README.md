# Level 2
# Task 4 · Unveiling the Android App Market (Google Play Store Analysis)

## Objective
Perform a comprehensive data analysis of the Google Play Store ecosystem — cleaning messy real-world data, exploring app categories, analysing ratings and pricing trends, and conducting sentiment analysis on user reviews.

## Tech Stack
Python, pandas, numpy, matplotlib, seaborn, NLTK (VADER), scikit-learn (KMeans concepts), Plotly, Jupyter Notebook

## Datasets
- `googleplaystore.csv` — app listing data (category, rating, size, installs, price, etc.)
- `googleplaystore_user_reviews.csv` — user review text data

## What This Notebook Covers
- Loading and cleaning both datasets (fixing data types, e.g. "Installs" stored as strings, handling nulls and duplicates)
- Category analysis: app distribution across categories
- Ratings analysis: rating distribution and trends
- Size vs. Installs analysis via scatter plots
- Free vs. Paid app distribution
- Estimated revenue calculation (Installs × Price) for paid apps
- Sentiment analysis on user reviews using VADER (NLTK)
- Merging review sentiment with app category data
- Sentiment breakdown by category (visualized)
- Interactive Plotly scatter chart for paid apps

## Key Findings / Conclusion
Three data-driven insights for a developer planning to launch a new app:
1. Many app categories are overcrowded, making differentiation critical.
2. Free apps dominate installs, so paid apps need a strong value proposition to justify pricing.
3. User sentiment varies notably by category, highlighting where user experience expectations are highest.

## How to Run
1. Open `Google_Play_Store_Analysis.ipynb` in Jupyter Notebook.
2. Ensure `googleplaystore.csv` and `googleplaystore_user_reviews.csv` are in the same directory.
3. Run all cells sequentially (the notebook downloads the VADER lexicon automatically via `nltk.download`).