# transport-delay-predictor
# 🚌 Predict Public Transport Delays Using Weather & Events

## Problem Statement
Build a model that predicts public transport delays based on 
external factors like weather conditions and city events.

## Dataset
[Public Transport Delays with Weather and Events](https://www.kaggle.com/datasets/khushikyad001/public-transport-delays-with-weather-and-events)

## Skills Practiced
- Data cleaning
- Feature engineering
- Time-based analysis
- Regression models

## Approach
1. Explored how rain, snow, and extreme temperatures affect delays
2. Analyzed whether major city events increase delay probability
3. Trained multiple models to predict delay duration

## Models Used
| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 5.53 min | 6.38 min | -0.0164 |
| Random Forest | 5.57 min | 6.53 min | -0.0622 |
| XGBoost | 5.85 min | 6.94 min | -0.2260 |

## Key Finding
Weather severity was the #1 most important feature 
for predicting transport delays.

## Tech Stack
Python · Pandas · Scikit-learn · XGBoost · Matplotlib · Seaborn

## How to Run
Open the notebook directly in Colab using the button above!
