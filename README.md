# Sentiment Analysis on Text Data using Logistic Regression

## Overview

This Jupyter notebook aims to perform sentiment analysis on a text corpus, categorizing each phrase into its corresponding sentiment class. Sentiment classes in the given dataset are represented as numerical labels. The notebook employs Logistic Regression—a machine learning algorithm from Scikit-Learn—as the classifier. Additionally, it includes hyperparameter tuning via GridSearchCV to improve model performance.

## What is Sentiment Analysis?

Sentiment Analysis is the computational study of people's opinions, sentiments, emotions, or attitudes towards various entities like products, services, or events. In this notebook, we are particularly interested in classifying phrases into predefined categories of sentiment (e.g., positive, neutral, negative).

## Workflow

1. **Data Loading**: The notebook starts by loading training and test data from `.tsv.zip` files into Pandas DataFrames.
2. **Data Inspection**: The data is inspected for null values and data types for each column.
3. **Text Vectorization**: The text data ('Phrase' column) is transformed into a numerical format using CountVectorizer.
4. **Data Splitting**: The dataset is split into training and validation sets.
5. **Model Building**: A Logistic Regression model is trained on the training set.
6. **Evaluation**: The model's performance is evaluated using the accuracy metric on the validation set.
7. **Hyperparameter Tuning**: GridSearchCV is used to find the best hyperparameters for the Logistic Regression model.
8. **Optimized Model**: An optimized Logistic Regression model is built and evaluated based on the best parameters obtained from GridSearchCV.

## Requirements

- Python 3.9
- Pandas
- Scikit-Learn