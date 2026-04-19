US Economic Indicators Analysis using FRED API

A Python-based data analysis project that pulls real-time economic data 
from the Federal Reserve (FRED API) and visualizes key indicators across 
all 50 US states.

## What this project does:
- Fetches live economic data using the FRED API (no manual CSV downloads)
- Analyzes Unemployment Rate and Labor Force Participation Rate by state
- Merges multiple time-series datasets into a single pandas DataFrame
- Creates interactive visualizations using Plotly Express
- Compares state-level trends during key periods like COVID-19 (2020-2022)

## Tools & Libraries used:
- Python
- pandas
- numpy
- matplotlib
- plotly
- fredapi

## Key Features:
- Reusable code for fetching any FRED economic series
- Clean and structured data pipeline
- Interactive charts for all 50 US states
- Side by side comparison of unemployment vs participation rates

## Data Source:
Federal Reserve Economic Data (FRED) - St. Louis Fed
