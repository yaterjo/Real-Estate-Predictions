# Property Price Prediction Project

## Overview
This repository contains the code and documentation for a property price prediction project focused on the Puerto Rico area. The project aims to develop a machine learning model that predicts property prices based on various features such as the number of bedrooms, bathrooms, lot size, house size, and location.

## Table of Contents
- [Business Problem](#business-problem)
- [Data Insights](#data-insights)
- [Data Preparation and EDA](#data-preparation-and-eda)
- [Models](#models)
- [Results](#results)
- [Recommended Next Steps](#recommended-next-steps)
- [Requirements](#requirements)
- [Usage](#usage)


## Business Problem
The goal of this project is to assist real estate agents and buyers in understanding the market value of properties in Puerto Rico. By developing a predictive model, stakeholders can make informed decisions when buying or selling properties.

## Data Insights
- The dataset used in this project focuses exclusively on properties in Puerto Rico.
- Initial exploration revealed correlations between property prices and key attributes such as location and property size.

## Data Preparation and EDA
- Preprocessing steps included handling missing values, outliers, and encoding categorical variables.
- Exploratory Data Analysis (EDA) was conducted to visualize distributions and relationships between features and the target variable.

## Models
- Ensemble methods including Random Forest, AdaBoost, Gradient Boosting, and XGBoost were explored for modeling.
- Hyperparameter tuning and cross-validation were performed to select the best-performing model.

## Results
- The optimized Random Forest model achieved an average Mean Absolute Error (MAE) of approximately $439,368.13.
- Cross-validation confirmed the model's reliability and generalization ability.

## Recommended Next Steps
- Further optimization through fine-tuning hyperparameters and exploring additional feature engineering techniques.
- Investigate alternative modeling techniques such as deep learning.
- Deploy the optimized model for real-world predictions.

## Requirements
- Python 3
- Required libraries: pandas, numpy, scikit-learn, xgboost, shap (for model interpretation)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yaterjo/property-price-prediction.git
