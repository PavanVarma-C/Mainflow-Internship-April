#  House Price Prediction using Linear Regression

This project applies regression analysis on a real estate dataset to predict house prices using Python and Scikit-Learn.

##  Dataset

- Source: `housing_train.csv` (provided)
- Features: `Rooms`, `Bathroom`, `Landsize`, `BuildingArea`, and `Type`
- Target: `Price`

##  Steps Covered

1. **Data Exploration**: 
   - Checked missing values and distributions
   - Visualized numerical columns

2. **Preprocessing**:
   - Imputed missing values
   - Scaled numerical features
   - One-hot encoded the `Type` categorical feature

3. **Feature Selection**:
   - Correlation analysis to understand influential features

4. **Model Building**:
   - Split into train/test sets (80/20)
   - Trained using `LinearRegression` from `sklearn`

5. **Evaluation**:
   - Root Mean Squared Error (RMSE)
   - R² Score
   - Plots for predicted vs. actual values

##  Results

- **Model**: Linear Regression
- **Metrics**: RMSE and R²
- **Insight**: Shows how features like room count, land size, and building area affect price predictions

##  How to Run

1. Upload `housing_train.csv` to Colab
2. Run the `.ipynb` notebook step by step 


