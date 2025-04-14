# Supervised-Learning-Final-Project
Final project for Supervised Learning course: Predicting house prices using ML

# Ames Housing Price Prediction (Supervised Learning Final Project)

## Problem Statement
This project aims to predict house sale prices in Ames, Iowa using over 80 features. The goal is to build and evaluate supervised regression models to identify the most accurate predictor of housing prices.

## Data Source
- [Ames Housing Dataset on Kaggle](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)
- De Cock, D. (2011). *Ames, Iowa: Alternative to the Boston Housing Data*. Journal of Statistics Education.

## Methods
- Data Cleaning and Imputation
- Skewness Correction and Feature Engineering
- EDA (Heatmaps, Pair Plots, Distributions)
- Linear, Ridge, Lasso and Random Forest, RF Grid Search Models
- Hyperparameter Tuning with GridSearchCV
- Evaluation with Cross-Validated RMSE

## Results
| Model                       |   CV RMSE |
|-----------------------------|-----------|
| Random Forest (Grid Search) |  **0.150467** |
| Random Forest               |  0.151198 |
| Ridge Regression            |  0.167910 |
| Lasso Regression            |  0.167942 |
| Linear Regression           |  0.175412 |

## Takeaways
- Random Forest significantly outperformed linear models
- Feature transformations and careful preprocessing were key
- Further improvements could include XGBoost, deployment, or model interpretability

## Files Included
- `Supervised Learning Final Project.ipynb`: Main notebook
- `AmesHousing.csv`: Dataset used for modeling
- `README.md`: This file
