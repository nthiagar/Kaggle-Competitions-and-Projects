# Kaggle Competitions and Projects

## Overview
This repository contains a collection of data analysis and machine learning projects, including competition submissions from Kaggle.

### 1. Daily Temperature of Cities
- **File:** `Daily Temp of Cities/daily-temp-of-cities.ipynb`
- **Description:** Analyzes and visualizes daily temperatures of major cities.
  - Cleans data for outliers and missing values.
  - Plots the highest and lowest temperature increases from 1995 to 2019.
  - Maps average temperature differences globally for comparison.

### 2. Titanic Competition
- **File:** `Titanic Competition/Titanic ML Submission.ipynb`
- **Description:** Predicts survival on the Titanic using machine learning models.
  - Handles missing data in 'Age', 'Fare', and 'Embarked'.
  - Applies one-hot encoding to categorical features.
  - Trains RandomForest, XGBoost, KNeighbors, and GradientBoosting classifiers, stacking predictions with XGBoost for final submission.

### 3. Predict Future Sales Competition
- **File:** `Predict Future Sales Competition/Predict Future Sales Submission 1.ipynb`
- **Description:** Predicts total sales for the next month using machine learning.
  - Prepares data by dropping unnecessary columns and training a RandomForestRegressor model.
  - Generates predictions and saves results to submission.csv.

- **File:** `Predict Future Sales Competition/Predict Future Sales Submission 2.ipynb`
- **Description:** Collaborative effort with Ajay Kumaar.
  - Cleans data by handling missing values, extracting date-related features, and encoding categorical variables.
  - Trains multiple classifiers (RandomForestClassifier, XGBClassifier, KNeighborsClassifier, SVC) and uses stacking for final predictions.

## Data Sources
- [Daily Temperature of Major Cities](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities)
- [Titanic Data](https://www.kaggle.com/competitions/titanic/data)
- [Predict Future Sales Data](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data)

## Collaboration
- The `Predict Future Sales Submission 2.ipynb` notebook was a collaboration with Ajay Kumaar.

## Usage
To explore these projects:
- Load respective data on Kaggle.
- Run the notebooks to reproduce the analyses and results.
