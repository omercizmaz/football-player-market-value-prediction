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

## Example Visualization
<img width="2571" height="1634" alt="actual_vs_predicted_ridge" src="https://github.com/user-attachments/assets/6ee0b154-b57e-4129-9a56-2a1cde46ef40" />

## Better Model
<img width="3402" height="1634" alt="better-model" src="https://github.com/user-attachments/assets/d6acdcb9-df12-46df-8e48-191a4ec45b7d" />
