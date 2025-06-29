# 🗺️ Crime Rate Trend Analysis

## Overview
This project analyzes crime rates across US states using clustering and geo-mapping techniques. It leverages a public dataset to reveal trends in crime categories and provides insights through advanced visualizations.

## Objective
- Identify crime patterns by state and category.
- Cluster US states based on crime intensity and type.
- Visualize crime trends using choropleths, bar plots, and cluster profiles.

## Dataset & Inputs
- Dataset: Uploaded CSV file (`crime_data.csv`) from Kaggle
- Features include: `State`, `Crime_Type`, `Crime_Score`, etc.

## Technologies Used
- Python (pandas, matplotlib, seaborn, plotly, scikit-learn)
- Jupyter Notebook for analysis

## How to Run
1. Clone the repo and install dependencies:
```bash
pip install pandas matplotlib seaborn plotly scikit-learn
```

2. Run the Jupyter Notebook (`Crime Rate Trend Analysis.ipynb`) in your IDE or JupyterLab.

## Workflow
- Data Cleaning & Summary Stats
- Trend Analysis by Crime Type & State
- Geo-Mapping using Plotly Choropleth
- State Clustering using KMeans

## Results
- Top crimes by frequency and score.
- State clusters reveal regional crime intensity patterns.
- Choropleth maps provide intuitive visual insights.

## Key Takeaways
- Some states show consistently high crime scores across multiple types.
- Clustering enables profiling states into similar crime behavior groups.

## Future Enhancements
- Add year-wise trend analysis.
- Integrate socio-economic data to correlate with crime.

---
