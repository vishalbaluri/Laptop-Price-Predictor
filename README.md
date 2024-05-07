

# Laptop Price Prediction Project

This project is aimed at predicting the prices of laptops based on various features such as CPU, GPU, RAM, storage, operating system, and others. The prediction models are built using machine learning algorithms in Python.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Exporting the Model](#exporting-the-model)

## Dataset

The dataset used in this project is obtained from a CSV file named `laptop_data.csv`. It contains information about various laptops including their specifications and prices.

## Project Structure

- `laptop_price_prediction.ipynb`: Jupyter notebook containing the Python code for data preprocessing, exploratory data analysis, model building, and evaluation.
- `df.pkl`: Pickle file containing the preprocessed DataFrame.
- `pipe.pkl`: Pickle file containing the trained machine learning pipeline.

## Data Preprocessing

- Loaded the dataset using pandas.
- Cleaned and preprocessed the data by handling missing values, removing duplicates, and converting data types.
- Extracted relevant features such as RAM, CPU brand, GPU brand, storage type, and operating system.

## Exploratory Data Analysis (EDA)

- Visualized the distribution of laptop prices and explored relationships between price and various features.
- Conducted analysis on CPU, GPU, RAM, storage, operating system, and other features to understand their impact on laptop prices.

## Model Building

- Implemented several machine learning algorithms for regression including Linear Regression, Ridge Regression, Lasso Regression, K-Nearest Neighbors, Decision Tree, Support Vector Machine (SVM), Random Forest, ExtraTrees, AdaBoost, Gradient Boost, XGBoost, Voting Regressor, and Stacking.
- Utilized one-hot encoding for categorical features and pipeline for preprocessing and model building.
- Tuned hyperparameters for certain models to improve performance.

## Evaluation

- Evaluated the performance of each model using R-squared (R2) score and Mean Absolute Error (MAE).
- Chose the best performing model based on evaluation metrics.

## Exporting the Model

- Exported the preprocessed DataFrame and the trained machine learning pipeline for future use.

---
