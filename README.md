# Smartphone Price Prediction Model

## Overview
This project builds a machine learning model to predict smartphone prices based on various product features extracted from a cleaned smartphone listings dataset. The objective is to develop a robust regression model that can estimate the price range of new smartphone listings accurately.

## Dataset
- The dataset (`smartphones_dataset.csv`) contains cleaned and preprocessed smartphone attributes including brand, specifications, release year, and more.
- Data cleaning and feature engineering were performed to optimize predictive power and model performance.

## Model Development
- The Jupyter notebook (`pred_model.ipynb`) documents the entire modeling workflow:
  - Exploratory data analysis to understand feature distributions and relationships.
  - Feature selection and preprocessing including encoding categorical variables.
  - Training and evaluation of multiple regression models to find the best fit.
  - Model tuning and cross-validation to enhance accuracy and avoid overfitting.
  
## Tools and Libraries
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- Jupyter Notebook for interactive development and visualization

## Key Outcomes
- Developed a final regression model with optimized hyperparameters.
- Achieved satisfactory performance metric on validation data.
- The model can be utilized to estimate smartphone prices for new inputs, aiding sellers or buyers in making informed decisions.

## Usage Instructions
1. Load the cleaned dataset `smartphones_dataset.csv`.
2. Run the `pred_model.ipynb` notebook to follow the model building process or to train and evaluate the model yourself.
3. Use the trained model to predict prices on new smartphone feature sets.
