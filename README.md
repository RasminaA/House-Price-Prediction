# House Price Prediction

## Overview

This project uses machine learning to predict house prices based on property features from the Ames Housing dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

## Project Workflow

1. Data loading and exploration
2. Missing-value analysis and preprocessing
3. Exploratory data analysis
4. Feature engineering
5. Categorical variable encoding
6. Train-validation split
7. Machine learning model training
8. Model evaluation
9. Model comparison
10. House price prediction

## Feature Engineering

Two additional features were created:

- **TotalArea** – Total basement and floor area
- **HouseAge** – Age of the house based on the year built

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## Model Results

| Model | R² Score |
|---|---:|
| Linear Regression | 0.6427 |
| Decision Tree | 0.7922 |
| Random Forest | 0.8821 |
| Gradient Boosting | 0.8949 |
| XGBoost | **0.9036** |

XGBoost achieved the best validation performance with an **R² score of 0.9036**.

## Dataset

The project uses the Ames Housing dataset containing 1,460 training records and multiple numerical and categorical features related to residential properties.

## Project Output

The trained XGBoost model was also used to generate house price predictions for the test dataset.
