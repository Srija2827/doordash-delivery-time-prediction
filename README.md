# Food Delivery Time Prediction

## Overview
This project predicts food delivery time using machine learning techniques.

## Models Used
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression

## Best Model
XGBoost

Performance:
- MAE: 3.04 minutes
- MSE: 14.41
- R² Score: 0.84

# Why XGBoost Performed Best

XGBoost achieved the highest performance among all evaluated models with an R² score of 0.84 and an MAE of 3.04 minutes.

The superior performance of XGBoost can be attributed to the following factors:

- XGBoost captures complex non-linear relationships between features and delivery time.
- It builds trees sequentially, where each new tree focuses on correcting the errors made by previous trees.
- It effectively combines information from multiple important features such as delivery partner ratings, traffic density, weather conditions, and multiple deliveries.
- XGBoost includes regularization techniques that help reduce overfitting while maintaining high predictive accuracy.
- The dataset contains complex interactions between operational factors and delivery time, which are better modeled by boosting algorithms than by linear models.

As a result, XGBoost slightly outperformed Random Forest and significantly outperformed linear regression-based models.

## Key Findings
- Tree-based ensemble models significantly outperformed linear models.
- Multiple deliveries, traffic density, weather conditions, and delivery partner ratings were the most influential features.
- Distance showed only a moderate correlation (0.327) with delivery time.

## Technologies
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
