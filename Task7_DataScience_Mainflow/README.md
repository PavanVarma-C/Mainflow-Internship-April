# Data Analysis & Data Science with Python  
## Task - 7: Dimensionality Reduction & Stock-Price Forecasting

### Files Included
- **TCS_historical_data.csv**  
  Raw daily price history for TCS (DATE, CLOSE, OPEN, VOLUME,...)   
- **Task7_DataScience_Mainflow.ipynb**  
  Complete workflow: PCA on Iris + ARIMA forecasting on TCS prices   

---

## Overview
This repository demonstrates two common data-science pipelines in one project:

1. **Dimensionality Reduction (General EDA)**  
   - Apply PCA to the built-in *Iris* dataset  
   - Visualise clusters in 2-D and interpret explained variance  
2. **Stock-Price Analysis & Forecasting (TCS)**  
   - Analyse historical TCS closing prices  
   - Train a univariate ARIMA model to forecast future closing values  

---
  

## 1. Dimensionality Reduction (Iris + PCA)

**Objective:**  
Reduce the four original Iris features to two principal components and visualise species clusters.

**Key Steps:**
- Load **Iris** from `sklearn.datasets`
- Standardise features with `StandardScaler`
- Apply `PCA(n_components=2)`
- Plot PC1 vs PC2 coloured by species
- Display explained variance ratios and loadings

---

## 2. Stock-Price Forecasting (TCS)

**Objective:**  
Model and forecast TCS closing prices using ARIMA.

**Key Steps:**
- Read and clean `TCS_historical_data.csv`
- Select columns: `DATE`, `CLOSE`, `OPEN`, `VOLUME`
- Parse `DATE` → datetime, sort, set as index, forward-fill gaps
- Exploratory plots: time series, returns histogram, monthly boxplots
- Train/test split (80 % / 20 %)
- Auto-select ARIMA order via `pmdarima.auto_arima`
- Fit `statsmodels.tsa.arima.ARIMA`
- Forecast and evaluate: MAE, RMSE, MAPE
- Plot Actual vs Predicted series
 

