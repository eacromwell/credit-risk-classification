# Module 20 Challenge | Credit Risk Classification

In this project, we tackled the challenge of building a model to identify loan risk using historical lending activity data. We followed a step-by-step approach to preprocess the data, train a logistic regression model, and evaluate its performance. After importing necessary modules and reading the dataset into a Pandas DataFrame, we separated the data into labels and features. We then split the data into training and testing sets using the train_test_split function, ensuring reproducibility by setting a random state.

To address class imbalance, we employed the RandomOverSampler from the imbalanced-learn library to resample the training data, resulting in an equal representation of healthy and high-risk loans. We trained a logistic regression model using the resampled data and evaluated its performance on the testing set. The classification report and evaluation metrics showcased the model's ability to predict both classes effectively. The model demonstrated high precision, recall, and F1-scores for both healthy loans (class "0") and high-risk loans (class "1"), indicating its capacity to make accurate predictions for loan risk.

This project emphasized key steps in building and evaluating a predictive model, including data preprocessing, model training, resampling techniques for handling class imbalance, and comprehensive performance assessment. By systematically approaching the challenge, we achieved a well-performing logistic regression model capable of identifying loan risk, with a particular focus on balanced performance for both classes.

# Figure 1. - Example of Classification Report

![Fig1_Classification_Report](https://github.com/eacromwell/credit-risk-classification/assets/123791177/551d013b-28a7-4751-8ded-511d017d7780)

