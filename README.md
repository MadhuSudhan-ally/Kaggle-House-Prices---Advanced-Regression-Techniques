# Kaggle-House-Prices---Advanced-Regression-Techniques
This project focuses on predicting house prices for the Kaggle House Prices: Advanced Regression Techniques competition. Using a dataset of 79 features describing residential properties in Ames, Iowa, the goal is to build machine learning models that accurately estimate home sale prices.
🏡 House Prices – Kaggle Competition

This repository contains my work for the Kaggle House Prices: Advanced Regression Techniques competition.
The goal is to predict residential home prices in Ames, Iowa using 79 property features.

Contents

submission.csv – Baseline model submission (Public LB: 0.1498, Rank ~3070)
submissionxgb.csv – Xgboost (Public LB: 0.14198, Rank ~2970)
Notebook – Full preprocessing, feature engineering, and model training pipeline

Overview

Models used: RandomForest, Ridge Regression, HistGradientBoosting, XGBoost (planned)
Preprocessing includes ordinal encoding, missing value handling, feature engineering
Log-transformed target (log1p(SalePrice)) with 5-fold cross-validation
Leak-free target encoding applied to Neighborhood
