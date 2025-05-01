# Task 1 – Student Performance Analysis using Python

This project presents an analysis of student performance using the `student-mat.csv` dataset. The analysis is conducted entirely in Python using fundamental libraries only — ensuring clear understanding of data handling and visualization techniques.

## Files in This Folder
- `Task1_DataScience_Mainflow.ipynb` — Jupyter Notebook with code, visualizations, and explanations.
- `student-mat.csv` — Dataset containing student data from a Math course.

## Tasks Performed

### 1. Data Loading
- Loaded dataset using `pandas.read_csv()`.
- Displayed the first few rows.

### 2. Data Exploration
- Checked for missing values.
- Explored column data types and dataset shape.

### 3. Data Cleaning
- Removed duplicate entries.
- Verified dataset consistency (no missing values present).

### 4. Data Analysis
- Computed average final grade (G3).
- Counted students scoring above 15 in G3.
- Measured correlation between weekly study time and G3.
- Compared average G3 scores by gender.

### 5. Data Visualization
- Histogram of final grades (G3).
- Scatter plot: Study time vs G3.
- Bar chart: Average G3 by gender.

## Tools & Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

> Note: No advanced libraries like `scipy`, `plotly`, or `sklearn` were used. This was intentional to focus on core concepts.

##  Key Findings
- **Average Final Grade (G3)**: ~10.42  
- **Students Scoring Above 15**: 40  
- **Study Time and G3 Correlation**: 0.10 (weak positive)  
- **Gender Comparison**: Males scored slightly higher on average

##  Learning Outcomes
- Mastered data exploration, cleaning, and aggregation using pandas
- Understood basic statistical measures and correlations
- Built clear, meaningful visualizations
- Practiced modular, well-documented notebook structure

---

