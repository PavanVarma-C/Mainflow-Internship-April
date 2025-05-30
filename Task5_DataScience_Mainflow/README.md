# Task 5: Classification Tasks Overview

This repository contains a Jupyter notebook that implements two classification tasks in Python:

1. **Student Pass/Fail Prediction** (synthetic dataset)  
2. **Sentiment Analysis** on the IMDB movie-review dataset

---

## 📋 Contents

- `Task5_DataScience_Mainflow.ipynb`  
  - Task 1: Generate and analyze a synthetic student dataset, train & evaluate a Logistic Regression model  
  - Task 2: Upload and preprocess `IMDB Dataset.csv`, vectorize text, train & evaluate a Logistic Regression sentiment classifier  
- `README.md` (this file)

---
 
### In VSCode

- Upload the notebook.  
- Run the first code cell to install dependencies and download spaCy models.  
- For **Task 2**,  upload `IMDB Dataset.csv` from your local folder.

---

## 🛠️ Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn spacy
python -m spacy download en_core_web_sm
