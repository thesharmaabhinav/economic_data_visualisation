# economic_data_visualisation
Time Series Analysis of S&amp;P 500, Unemployment Rate, and Participation Rate data pulled from FRED API

📌 Project Overview

This project performs a time series analysis of:

S&P 500 Index

Unemployment Rate (by U.S. state)

Labor Force Participation Rate (by U.S. state)

The unemployment rate and participation rate datasets are pulled from the Federal Reserve Economic Data (FRED) API.
Data is analyzed, cleaned, transformed, and visualized to uncover trends and relationships over time.

📊 Data Sources

FRED API – Monthly unemployment and participation rate data by U.S. state

S&P 500 Data – Pulled from FRED or another compatible market data source

🛠 Data Preparation

Data Gathering

Pulled monthly frequency unemployment and participation rate data for each U.S. state from FRED API.

Pulled S&P 500 index data for the same period.

Data Cleaning & Wrangling

Removed irrelevant columns.

Dropped rows containing NaN values.

Aligned all datasets to have a uniform date range (late 1970s – 2025) since some data started in the 1940s.

Transformation

Adjusted column formats for consistency.

Standardized date formats and index structure.

Combined datasets where necessary for comparative analysis.

🔍 Analysis & Visualization

Time series plots to observe historical trends.

Comparative analysis of unemployment vs. participation rates.

Interactive visualizations using Plotly for better exploration.


📚 Technologies & Libraries Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib – static visualizations

Plotly – interactive visualizations

fredapi – data extraction from FRED

🚀 Key Insights

This analysis highlights:

Long-term trends in state-level unemployment and participation rates.


