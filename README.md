# Sales Forecasting with XGBoost

This project is a single-file notebook that builds a complete sales forecasting pipeline using XGBoost. It includes data preparation, feature engineering for time series, model training, evaluation with multiple metrics, and several plots to validate performance.

## Contents
- Data loading and preprocessing
- Time series feature engineering
- Training an XGBoost regression model
- Evaluation with multiple metrics
- Curves and plots (actual vs predicted, residuals, error distribution)
- Feature importance analysis
- Manual input cell to test the model (if included in the notebook)

## Model
The notebook uses XGBoost Regressor, a gradient boosting algorithm widely used for regression tasks. It performs well on structured/tabular data and can capture nonlinear patterns.

## Metrics
The notebook reports:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Coefficient of Determination)
- MAPE (Mean Absolute Percentage Error)
- SMAPE (Symmetric Mean Absolute Percentage Error)

## Visualisations
The notebook includes:
- Actual vs Predicted curve
- Residuals vs Predictions scatter plot
- Error distribution histogram
- Feature importance bar chart (XGBoost)

## Requirements
Python 3.9+ recommended.

Dependencies:
- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- jupyter

