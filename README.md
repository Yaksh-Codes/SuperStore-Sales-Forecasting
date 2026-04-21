# Superstore Sales Time Series Forecasting 📈

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)

## 📌 Project Overview
This project performs an end-to-end time series analysis and forecasting on the Superstore Sales dataset. The primary objective is to analyze historical sales data, identify seasonal patterns, and build predictive models to forecast future sales for specific product categories like **Furniture** and **Office Supplies**.

## 🚀 Key Features
- **Exploratory Data Analysis (EDA):** Data cleaning, missing value checks, and category-level sales distribution.
- **Data Preprocessing:** Resampling time series data to monthly start frequency (MS) for smooth pattern recognition.
- **Hyperparameter Tuning:** Automated grid search using `itertools` to find the optimal PDQ and Seasonal PDQ parameters.
- **Predictive Modeling:** Implementing **SARIMAX** (Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors) to forecast future sales.
- **Model Evaluation:** Analyzing AIC scores and model diagnostic plots to ensure reliability.

## 🛠️ Tech Stack
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`
- **Time Series Modeling:** `statsmodels`

## 📂 Repository Structure
```text
├── data/
│   └── SuperStore Sales DataSet.xlsx    # Raw dataset (ensure this is placed here)
├── notebooks/
│   └── SuperStore_Time_series.ipynb     # Main analysis and forecasting notebook
├── .gitignore                           # Git ignore rules
├── requirements.txt                     # Environment dependencies
└── README.md                            # Project documentation
