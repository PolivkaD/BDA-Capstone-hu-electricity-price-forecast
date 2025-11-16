# BDA-Capstone-hu-electricity-price-forecast
MSc IT for Business Data Analytics – Hungarian day-ahead electricity price forecasting project

# Hungarian Day-Ahead Electricity Price Forecasting (BDA Capstone Project)

MSc in IT for Business Data Analytics – Business Data Analytics Project  
Author: Dávid Polivka  

## Project overview

This repository contains the code for my Business Data Analytics Project.  
The goal is to forecast **day-ahead electricity prices in the Hungarian (HUPX) market** using
ENTSO-E data, weather variables (ERA5), and selected macro / fuel price indicators.

The main objectives are:
- collect and clean ENTSO-E and weather data for Hungary and the region,
- explore the relationship between load, generation mix, weather and prices,
- build baseline and advanced ML/TS forecasting models,
- evaluate model performance with strict out-of-sample validation,
- derive business-relevant insights for market participants.

## Repository structure

- `data/` – raw and processed data (not included in GitHub; stored locally only).
- `notebooks/` – Jupyter notebooks for EDA, feature engineering and modelling.
- `src/` – reusable Python modules (data loading, feature engineering, modelling).
- `reports/figures/` – figures used in the written report.
- `requirements.txt` – Python dependencies for reproducing the environment.

## How to run

1. Create and activate a Python environment (Python 3.10+ recommended).
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
