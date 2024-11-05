# Sentiment Analysis of Hotel Review

This project involves building a sentiment analysis model to classify hotel reviews as positive or negative using Logistic Regression. The model is trained on text data from hotel reviews and evaluated on its performance in predicting sentiment.

# Project Overview
This repository contains a sentiment analysis pipeline for classifying hotel reviews. The pipeline uses the TF-IDF vectorization technique for feature extraction and Logistic Regression for classification.

# Features
1)TF-IDF Vectorization: Converts text data into numerical features.

2)Logistic Regression: Classifies reviews into positive or negative sentiments.

3)Evaluation: Provides metrics such as accuracy, precision, recall, and confusion matrix.

# Data Sources
https://www.kaggle.com/datasets/anu0012/hotel-review

# Model

Pipeline
The project uses a machine learning pipeline comprising:
TF-IDF Vectorizer: Converts text reviews into numerical feature vectors.

Logistic Regression: Trains on the feature vectors to classify sentiments.

# The model is trained with:
Training Data: A portion of the dataset used to fit the model.

Validation: Split from the training data to tune hyperparameters.


# Evaluation
Model performance is evaluated using:
Accuracy: The proportion of correctly classified reviews.

Precision: The proportion of positive reviews that are correctly identified.

Recall: The proportion of actual positive reviews identified.
