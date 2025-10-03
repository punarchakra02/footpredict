# Football Match Prediction

This project aims to predict the outcome of some Premier league football matches using machine learning.

## Files

*   `prediction.ipynb`: A Jupyter notebook that contains the entire workflow, from data loading and preprocessing to model training and evaluation.
*   `matches.csv`: The dataset containing historical football match data, from the 2020-21 and the 2021-22 Premier league seasons

## Overview

The notebook `prediction.ipynb` uses the data from `matches.csv` to train a Random Forest Classifier. The model is then used to predict match winners. The notebook includes steps for:

1.  **Data Loading and Cleaning:** Reading the `matches.csv` file and preparing the data for modeling.
2.  **Feature Engineering:** Creating new features from the existing data to improve model performance.
3.  **Model Training:** Training a `RandomForestClassifier` on a subset of the data.
4.  **Prediction and Evaluation:** Making predictions on a test set and evaluating the model's accuracy and precision.

