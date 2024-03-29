# Predicting Property Prices in Puerto Rico

## Overview
This repository contains the code and documentation for a property price prediction project focused on the Puerto Rico area under $1,000,000. The project aims to develop a machine learning model that predicts property prices based on various features such as the number of bedrooms, bathrooms, lot size, house size, and location.

## Table of Contents
- [Business Problem](#business-problem)
- [Data Insights](#data-insights)
- [Data Preparation and EDA](#data-preparation-and-eda)
- [Models](#models)
- [Results](#results)
- [Recommended Next Steps](#recommended-next-steps)
- [Requirements](#requirements)



## Business Problem
The objective of this project is to develop a machine learning model to predict property prices in Puerto Rico. Accurate property price predictions are crucial for real estate agents and potential buyers to make informed decisions in the housing market. By leveraging data-driven techniques, we aim to provide insights into the factors influencing property prices and improve the understanding of the market dynamics in Puerto Rico.

## Data Insights
The dataset used in this project contains various features such as the number of bedrooms, bathrooms, lot size, house size, and location (city, state, zip code). Through exploratory data analysis (EDA), we gained insights into the distribution of property prices and the relationships between different features. We identified potential outliers and missing values that required preprocessing before model training.

## Data Preparation and EDA
To prepare the data for modeling, we performed several preprocessing steps, including filtering the dataset to focus on properties in Puerto Rico, handling missing values using imputation techniques, encoding categorical variables, and removing outliers. Exploratory data analysis helped us understand the distribution and relationships of features, guiding our preprocessing decisions.
![GitHub Logo](/pictures/matrix.JPG)
![GitHub Logo](/pictures/outlierb4.png)
![GitHub Logo](/pictures/distribution.png)

## Models
For modeling, we selected the Random Forest regression algorithm due to its ability to handle complex relationships in the data and resist overfitting. We trained the model using the preprocessed dataset and fine-tuned hyperparameters using GridSearchCV to optimize performance. Additionally, we evaluated other regression models such as AdaBoost, Gradient Boosting, and XGBoost to compare their performance against Random Forest.

## Results
The final Random Forest model achieved promising results on the test set, with a Mean Absolute Error (MAE) of approximately 38,154 and an R² score of 0.92. These metrics indicate that the model explains about 92% of the variance in property prices. Evaluation on additional models provided insights into their comparative performance and potential areas for improvement.
![GitHub Logo](/pictures/MAE.JPG)
![GitHub Logo](/pictures/RSME.JPG)
![GitHub Logo](/pictures/R2.JPG)

## Recommended Next Steps
To further improve the model's performance, we recommend exploring additional features that may influence property prices, such as economic indicators, neighborhood characteristics, and property amenities. Additionally, conducting feature engineering and incorporating advanced modeling techniques could enhance predictive accuracy. Continuous monitoring and updating of the model based on new data and market trends are also essential for maintaining its relevance and effectiveness.

## Requirements
- Python programming language
- Libraries such as pandas, NumPy, scikit-learn, and matplotlib
- Jupyter Notebook for code execution and documentation
- Access to the dataset containing property features and prices in Puerto Rico
- Basic understanding of machine learning concepts and techniques
