# Natural-Gas-Price-prediction-using-SARIMAX
# Natural Gas Price Prediction

## Project Overview

This project focuses on analyzing and predicting natural gas prices using time series forecasting techniques. It includes data preprocessing, trend analysis, stationarity tests, and predictive modeling using machine learning techniques.

## Features
- **Data Exploration & Cleaning**: Handles missing values and detects trends.
- **Seasonality & Stationarity Analysis**: Uses statistical tests like the ADF test.
- **Time Series Forecasting**: Implements ARIMA, SARIMA, and other predictive models.
- **Visualization**: Generates insightful plots to analyze price trends.

## Dataset
- The project uses a dataset containing historical natural gas prices from **1990 to 2021**.
- Data is loaded from a CSV file and indexed by date.

## Installation
Ensure you have Python installed, then install dependencies:
```bash
pip install pandas numpy matplotlib statsmodels pmdarima
```

## How to Run
1. Load the dataset into a Pandas DataFrame.
2. Perform exploratory data analysis (EDA) and visualize trends.
3. Test for stationarity using ADF test.
4. Train and evaluate time series forecasting models.
5. Generate predictions and plot results.

Run the notebook using:
```bash
jupyter notebook Nat_Gas_Predection.ipynb
```

## Dependencies
- `pandas` – Data manipulation
- `numpy` – Numerical computations
- `matplotlib` – Data visualization
- `statsmodels` – Statistical modeling
- `pmdarima` – Automated ARIMA modeling

## Results
- The project identifies seasonality and non-stationarity in gas prices.
- Predictive models provide insights into future price trends.

---
This project is useful for financial analysts, energy traders, and researchers studying commodity price movements.
