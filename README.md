# Terrain Prices Regression – Kaggle Competition

Competition: Terrain Prices Regression

Platform: Kaggle

Evaluation Metric: R² Score

Final Private Score: 0.93

## Project Overview

This project was developed for the Kaggle Terrain Prices Regression Challenge, where the objective was to predict land plot prices using environmental, geographic, and economic features.

The dataset contains 40 mixed-type features describing terrain characteristics, accessibility, zoning, and local economic indicators. The target variable represents land price.

The goal was to build a regression model capable of capturing nonlinear relationships between features and land value.

## Dataset Information

Training Set: 1,500 samples

Test Set: 1,200 samples

Features: 40 total

Target: target (land price)

Feature Types

Categorical: location_type, land_use, zoning_code

Numerical: elevation, slope_deg, soil_quality, median_income_area, crime_rate, amenities_score, etc.

## Workflow

1. Data Preprocessing
2. Feature Selection
3. Train / Validation Split
4. Polynomial Feature Engineering
5. Feature Scaling
6. Model: ElasticNet Regression

## Model Performance
Model Version	Validation R²

ElasticNet (Polynomial + Scaling)	High Validation Performance

ElasticNet (Polynomial, No Scaling)	Lower Performance

Final Private Kaggle Score: 0.93

## Technologies Used

Python

Pandas

NumPy

Scikit-learn

  LabelEncoder
  
  PolynomialFeatures
  
  StandardScaler
  
  ElasticNet
  
  train_test_split
  
Kaggle Notebook Environment

Competition: https://www.kaggle.com/competitions/terrain-prices-reggression/overview
