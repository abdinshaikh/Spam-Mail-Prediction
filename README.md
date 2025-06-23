# Spam Mail Detection using Logistic Regression
- This project is a simple machine learning implementation that detects whether an email is spam or not using Logistic Regression. It uses a cleaned dataset of emails, processes them using TF-IDF vectorization, and builds a predictive model using scikit-learn.

## Features
- Preprocessing and cleaning of raw email data

- Conversion of text data to numerical features using TF-IDF

- Training a Logistic Regression model for classification

- Evaluating performance using accuracy score

## Dataset
- The dataset used is a CSV file containing labeled emails, where:

  1 = Spam

  0 = Not Spam (Ham)

- It is loaded and preprocessed using pandas and scikit-learn.

## Machine Learning Workflow
- Import Libraries: numpy, pandas, sklearn

- Load and Clean Data

- Feature Extraction: TF-IDF Vectorizer

- Model Training: Logistic Regression

- Model Evaluation: Accuracy metric

##  Model Performance
-Training Accuracy: 96.72%

-Test Accuracy: 97.04%

- These scores indicate that the model performs well and generalizes effectively to unseen data.

## Tech Stack
- Python

- Pandas

- Scikit-learn

- NumPy

