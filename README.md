# Renter's Union
#### Machine Learning Project by Alejandro Figueroa, Daniela Rivera, David Heller and Maya Wilson-Fernandez

## Overview
> We are a newly-formed union of renters that aim to bring transparency to rental pricing across the country. 

> This project entails creating a machine learning model that can predict the rental price of an apartment based on its features and attributes, as well as its proximity to services such as libraries, schools, and hospitals.

## Data Sources

> For this project, we used the following dataset:

[Apartment for Rent Classified](https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified)

[OpenStreetMap API](https://www.openstreetmap.org/#map=9/18.2235/-66.5927)

> Datasets after cleaning and selecting:

[Clean Data with Outliers](apartment_data.csv)
[Clean Data without Outliers](filtered_apartment_data.csv)

For this project we performed machine learning techniques for three different variations of the same dataset:

1. We initially evaluated the dataset using various regression models, focusing on numerical data. 
2. The target variable, price, was converted into categorical data by assigning labels (low, medium, and high) to different price ranges. This transformation allowed us to analyze the data using classification models.
3. We continued to improve our analysis using classification models by only focusing on the state of Florida.

## Machine Learning Techniques

> Feature Engineering
  
  - Encoding with GetDummies for categorical data

> Feature Scaling

  - Normalized numerical data with MinMaxScaler

> Feature Selection

  - Created a correlation matrix to understand the relationship between the features and the target
  - Performed a TrainTestSplit 

> Machine Learning Models 

  - KNN Regressor and Classifier
  - Linear Regression
  - Baggining and Pasting
  - Random Forest
  - AdaBoost
  - Gradient Boosting
  - Decision Tree

> Hyperparameter Tuning

  - For the KNN Regressor model (which had the best score for the numerical data evaluation) we fine tuned it's hyperparameters using Grid Search to further improve our score

## Key Findings

> For our numerical data, we were able to improve our score by fine tuning the hyperparameters

> Converting the target variable to categorical data and narrowing the focus to a specific state (Florida) both contributed to improved machine learning model performance.

> These strategies demonstrated the importance of data transformation and segmentation in achieving better results.

## Other URLs

[Presentation](https://docs.google.com/presentation/d/1_RpFE-3Vs1cLMoL0Wl2Is1rFOyco95_v2BUSNBoUGUo/edit#slide=id.g292a9bb486b_1_114)

[Trello](https://trello.com/b/6oKWCRzJ/machine-learning-project)
