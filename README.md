# Kaggle Stock Price Directional Move Prediction

This repository contains my solution for the Kaggle **Stock Price Directional Move Prediction** competition.

## Overview
The goal of this competition was to predict the next-period directional movement of stock price using technical indicator features.

## Result
- Public Leaderboard Rank: **7th out of 58 teams**
- Public Leaderboard Score: **0.695806**

## Approaches Tried
I experimented with multiple machine learning models:
- Logistic Regression
- LightGBM
- XGBoost Classifier
- Random Forest

## Workflow
The general pipeline included:
- Data loading
- Basic preprocessing
- Train-test split
- Feature scaling
- Model training and evaluation
- Experiments with class imbalance handling
- Threshold tuning

## Key Observation
Although I tried multiple advanced models and tuning strategies, a simple **Random Forest** model performed best for this competition. In some cases, additional tuning and experimentation reduced performance instead of improving it.

## Files
- `stock_prediction.ipynb` — final notebook used for training and experimentation
- `requirements.txt` — dependencies used for the project (optional)

## Skills Demonstrated
- Machine learning model comparison
- Feature preprocessing
- Experiment tracking
- Model evaluation
- Kaggle competition workflow
