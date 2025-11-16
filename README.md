# Hungarian Day-Ahead Electricity Price Forecasting (BDA Capstone)

MSc in IT for Business Data Analytics – Business Data Analytics Project  
Author: Dávid Polivka (PolivkaD)

## Overview

This repository contains the code and project structure for my Business Data Analytics Capstone Project.  
The goal is to forecast **day-ahead electricity prices in the Hungarian (HUPX) market** using:

- ENTSO-E market and system data
- Weather data (e.g. ERA5)
- Selected fuel and CO₂ price indicators

## Repo structure

- `data/` – raw and processed data (kept locally, not pushed to GitHub)
- `notebooks/` – Jupyter notebooks for EDA, feature engineering and modelling
- `src/` – reusable Python code (data loading, feature engineering, models)
- `reports/` – exported figures and other assets for the written report

## Next steps

1. Collect and clean ENTSO-E and weather data.
2. Explore relationships between load, generation mix, weather and prices.
3. Build baseline forecasting models and more advanced ML models.
4. Evaluate models with proper time-series validation.
5. Translate findings into business-relevant insights.

