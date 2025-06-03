# Synthetic Data Modeling Notebook

## Overview:
1. **Time Series Analysis**  
   - Generating a synthetic daily‐sales time series (with trend, seasonality, and noise)
   - Fitting an ARIMA(2, 1, 2) model
   - Forecasting the next 30 days and plotting results
2. **Classification with Logistic Regression**  
   - Creating a synthetic binary classification dataset via `sklearn.datasets.make_classification`
   - Training a `LogisticRegression` model
   - Evaluating performance (accuracy, confusion matrix, classification report)
  

## Files
- **Task6_DataScience_Mainflow.ipynb**  
  A Colab‐compatible Jupyter notebook containing: 
  - Code cells for data generation, model fitting, evaluation, and visualization

- **README.md**  
  This file.  

---

## Requirements
The notebook uses the following Python packages. In Google Colab, most are already installed, but you can install any missing ones with `pip`:

- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`
- `scikit-learn`

If you run locally (instead of Colab), you can install dependencies via:
```bash
pip install numpy pandas matplotlib statsmodels scikit-learn
