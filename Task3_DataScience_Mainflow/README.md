# Data Analysis & Data Science with Python  
**Task – 3: Customer Segmentation (K-Means Clustering)**  

---

## Files Included
| File | Description |
|------|-------------|
| **Customer_Segmentation_Task3.ipynb** | Jupyter notebook containing the full workflow: data cleaning, feature scaling, optimal-k search, K-Means clustering. |
| **Mall_Customers.csv** | Raw customer dataset ( *CustomerID, Age, AnnualIncome, SpendingScore,* etc.). |
| **clustered_customers.csv** | Same records as above **plus** a `Cluster` column produced by the notebook’s final K-Means model. |
| **README.md** | (this file) task description, steps, and requirements. |

---

## Overview
This task delivers a complete **customer-segmentation pipeline** in a single notebook.  
The goal is to group customers into behaviourally similar clusters so that marketing campaigns can be tailored more precisely.

---

## Project Structure  

| Key Step | Actions Performed |
|----------|------------------|
| **Data Cleaning** | • Checked for duplicates (none found) • Verified no missing values • Confirmed data types |
| **Descriptive Statistics** | • Calculated mean, median, std-dev, for all numeric features   |
| **Exploratory Visualisations** |  Pair-plot (*Age* vs *Income* vs *SpendingScore*)  |
| **Feature Scaling** | Applied `StandardScaler` to all numeric columns (essential for distance-based clustering). |
| **Optimal-k Search** | • Elbow plot (WCSS vs. *k* 1 – 10) • Mean silhouette scores  . |
| **K-Means Clustering** | Final model is currently fit with `k_optimal = 5` . |
| **Validation & Visuals** | • Silhouette plot for *k = 5* • Bar chart of cluster sizes • PCA 2-D scatter with centroids. |
 

---

## Technologies Used
- **Python** – Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Jupyter Notebook**  
- **Git & GitHub**

> **Windows MKL Note:**  
> To suppress the K-Means memory-leak warning on Windows, set these environment variables *before* importing NumPy/Scikit-learn:  
> `OMP_NUM_THREADS=1`, `MKL_NUM_THREADS=1`, `NUMEXPR_NUM_THREADS=1`.

---
