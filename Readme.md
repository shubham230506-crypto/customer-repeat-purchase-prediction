# Customer Repeat Purchase Prediction

## Overview
A machine learning project that predicts whether a customer will make another purchase based on historical transaction data.

## Objectives
- Clean and prepare retail transaction data.
- Perform customer-level feature engineering.
- Train and compare classification models.
- Evaluate predictions using accuracy, precision, recall, and F1-score.

## Dataset
Online Retail transaction dataset containing invoice details, product information, quantities, prices, customer IDs, dates, and countries.

## Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Features
- Number of orders
- Total spending
- Average order value
- Number of unique products purchased

## Models
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation
The models are compared using accuracy, precision, recall, and F1-score. In this project, Random Forest achieved the highest F1-score among the three tested models.

## How to Run
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Place the dataset in the expected location.
4. Open the notebook in Jupyter and run the cells.

## Future Improvements
- Improve recall for repeat purchasers.
- Perform cross-validation and hyperparameter tuning.
- Experiment with additional customer features.
