End-to-end machine learning project demonstrating regression modeling, evaluation, feature engineering, and diagnostics.

California Housing Price Prediction (Linear Regression)

This project builds and evaluates a linear regression model using the California Housing dataset from scikit-learn to predict median home values.

Project Overview

Loaded and explored housing dataset using pandas

Trained a Linear Regression model using scikit-learn

Evaluated performance using R², MAE, and RMSE

Compared actual vs predicted values

Conducted model improvement experiments:

Feature selection

Feature scaling (StandardScaler)

Residual analysis

Model Performance

R²: 0.5758

MAE: 0.5332 (~$53K average error)

RMSE: 0.7456 (~$74K error with penalty for large mistakes)

Key Insights

Median income and location strongly influence housing prices

Removing features slightly reduced performance

Scaling did not significantly change linear regression accuracy

Residual distribution shows balanced prediction errors

Files Included

housing_regression.py — main machine learning workflow

actual_vs_predicted.png — prediction visualization

residual_distribution.png — residual error distribution

Tools & Libraries

Python

pandas

scikit-learn

NumPy

matplotlib

How to Run
pip install scikit-learn pandas numpy matplotlib
python housing_regression.py

