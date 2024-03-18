#                                                     Big Mart Price Prediction Project

![download](https://github.com/Toja007/Big_mart/assets/131866743/be124c93-d850-4551-b1be-533d06af6c89)


This project aims to predict the prices of items sold in Big Mart stores using machine learning techniques. The dataset contains various features such as item weight, item visibility, item type, store size, and more.

# Table of Contents
Project Overview
Dataset
Feature Engineering
Modeling
Evaluation
Results and Insights
Usage
Dependencies

# Project Overview
In this project, I utilized machine learning models to predict the prices of items in Big Mart stores. I performed extensive feature engineering, model training, and evaluation to achieve accurate predictions.

# Dataset
The dataset used in this project contains information about various items sold in Big Mart stores. It includes features such as item weight, item visibility, item type, store size, and more. The target variable is the price of each item.

# Feature Engineering
I conducted feature engineering to preprocess the data and extract meaningful features for our models. This involved handling missing values, encoding categorical variables, scaling numerical features, and creating new features as needed.

# Modeling
I experimented with several machine learning models, including linear regression, decision trees, random forests, and gradient boosting. The models were trained using all 32 features as predictors to capture the relationships between the item attributes and their prices.

# Evaluation
Model performance was evaluated using various metrics such as mean squared error (MSE). I also plotted regression lines for each predictor to visualize the relationships with the target variable. Additionally, learning curves were plotted to analyze model performance with different training data sizes.

# Results and Insights
The final model achieved an accuracy of 726 mean absolute error on the test dataset, indicating its ability to predict item prices effectively. Through the analysis of regression lines and learning curves, we gained insights into the most influential predictors and model behavior under different training scenarios.

# Observation: 
The item MRP (Maximum Retail Price) appears to be the major contributor to the pricing of items. This suggests that the price set by the manufacturer plays a significant role in determining the selling price in Big Mart stores.

# Usage
To use the trained model for price prediction:

Install the necessary dependencies listed in the requirements.txt file.
Load the preprocessed data and the trained model.
Input the item attributes for which you want to predict the price.
Obtain the predicted price output from the model.
# Dependencies
Python 3
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
