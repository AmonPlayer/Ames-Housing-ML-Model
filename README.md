# Ames Housing Price Prediction

## Project Overview
This project applies machine learning to predict residential home prices in Ames, Iowa using a Random Forest regression model. The goal is to build a robust predictive model capable of accurately estimating sale prices based on a wide range of property features.

## Summary
The dataset includes both numerical and categorical variables, as well as missing values. A pipeline was implemented, incorporating categorical encoding, feature scaling, and streamlined preprocessing. A Random Forest Regressor was chosen for its ability to capture nonlinear relationships, handle high-dimensional data, and reduce overfitting, with hyperparameters tuned via RandomizedSearchCV using 5-fold cross-validation and RMSE as the scoring metric. The best model was evaluated on a test set using RMSE and R², demonstrating strong predictive performance. Key strengths include the end-to-end pipeline, robust cross-validation, and optimized hyperparameters, while future improvements could focus on feature importance analysis, comparison with Gradient Boosting models, and additional feature engineering.
