#  Football Player Market Value Prediction

This project aims to predict football players' market values using regression-based machine learning models.

## Project Overview
- Target variable: Current market value
- Models used:
  - Linear Regression
  - Polynomial Regression
  - Ridge Regression (RidgeCV)
  - Lasso Regression (LassoCV)
  - ElasticNet Regression
- Evaluation metrics:
  - R²
  - MAE
  - RMSE

##  Key Insights
- Polynomial regression achieved higher R² but suffered from overfitting.
- Regularized models (Ridge, ElasticNet) provided more stable and realistic predictions.
- Prediction errors increased for high-value players due to unobserved market factors.

## 📊 Example Visualization
![Actual vs Predicted](figures/actual_vs_predicted_ridge.png)
