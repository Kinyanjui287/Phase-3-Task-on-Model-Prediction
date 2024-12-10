# Phase-3-Task-on-Model-Prediction

## House Price Prediction Project

### Project Overview

This project focuses on predicting house sale prices using two different regression models:

Linear Regression (Ordinary Least Squares - OLS)
Random Forest Regressor

The goal is to evaluate the performance of these models in accurately predicting house prices and compare their results based on evaluation metrics such as R² and RMSE.

### Data Description

The dataset consists of housing features and their corresponding sale prices. After cleaning and preprocessing, the following key features were used in the modeling process:

OverallQual: Overall material and finish quality
GrLivArea: Above-grade (ground) living area square footage
GarageCars: Number of cars that can fit in the garage
GarageArea: Size of the garage in square feet
TotalBsmtSF: Total square footage of the basement
1stFlrSF: First-floor square footage
FullBath: Number of full bathrooms
TotRmsAbvGrd: Total number of rooms above ground (excluding bathrooms)
YearBuilt: Original construction year
YearRemodAdd: Remodel year

### Modeling Results

Two models were trained and evaluated:

1. Linear Regression
R² (R-Squared): 82.5%
Interpretation: Linear Regression explains approximately 82.5% of the variance in house prices based on the selected features.
Strengths: Simplicity and interpretability due to the OLS summary.
2. Random Forest Regressor
R² (R-Squared): 77.0%
Interpretation: Random Forest explains about 77.0% of the variance in house prices.
Strengths: Captures non-linear relationships between features and the target variable.
Weakness: Slightly lower performance compared to Linear Regression for this dataset.

### Conclusion

Linear Regression performed better on this dataset, achieving a higher R² score of 82.5%. This indicates that the relationship between features and house prices is mostly linear, making linear regression a suitable choice.
Random Forest, while slightly less accurate, provides additional insights such as feature importance and handles non-linearity better.