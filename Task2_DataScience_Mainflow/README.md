# Data Analysis & Data Science with Python  
## Task - 2: Exploratory Data Analysis (EDA)

### Files Included
- **`Sample - Superstore.csv`**: Raw dataset containing sales and business metrics.
- **`cleaned_data.csv`**: Cleaned version after handling missing values, duplicates, and formatting issues.
- **`Task2_DataScience_Mainflow.ipynb`**: Contains all steps from data cleaning to modeling.

---

## Overview

This repository contains a complete **Exploratory Data Analysis (EDA)** and **Predictive Modeling** project based on retail sales data. The objective is to analyze patterns in sales performance and build a regression model to predict sales based on key business metrics.

---

## Project Structure

### Project 1: General EDA
#### Objective:
Perform an in-depth EDA to identify trends, patterns, anomalies, and relationships within the dataset.

#### Key Steps:
- **Data Cleaning**:  
  - Removed duplicates  
  - Handled missing values using group-wise and global medians  
  - Converted date fields to datetime objects  

- **Statistical Summary**:  
  - Calculated key statistics (mean, median, std. dev, etc.)  
  - Identified variable correlations

- **Visualizations**:  
  - Histograms for distribution analysis  
  - Boxplots for outlier detection  
  - Heatmaps for correlation analysis  

---

### Project 2: Sales Performance Analysis
#### Objective:
Analyze sales trends and build a predictive model to estimate sales performance based on available features.

#### Key Steps:
- **EDA Visualizations**:
  - Time series plot of monthly sales trends
  - Scatter plot of Profit vs. Discount
  - Bar chart for sales by Region
  - Pie chart for sales by Category

- **Predictive Modeling**:
  - Trained a **Linear Regression Model** to predict `Sales` based on `Profit` and `Discount`
  - Evaluated using **R² score** and **Mean Squared Error (MSE)**

---

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Git & GitHub**


