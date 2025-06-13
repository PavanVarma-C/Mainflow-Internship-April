# Task 7 — Dimensionality Reduction & Stock-Price Forecasting

This mini-project contains two independent parts:

| Part | Goal | Dataset |
|------|------|---------|
| 1    | Reduce the **Iris** dataset to 2 principal components with PCA and visualise the clusters. | Built-in scikit-learn Iris dataset |
| 2    | Forecast closing prices for **TCS_historical_data.csv** with an **ARIMA** model. | Local CSV (DATE, CLOSE, OPEN, VOLUME) |

---

## 1. Quick-start

```bash
# 1️⃣  Create and activate a virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate

# 2️⃣  Install required packages
pip install -r requirements.txt    # see below for the full list

# 3️⃣  Launch Jupyter Lab / Notebook
jupyter lab                         # or: jupyter notebook
