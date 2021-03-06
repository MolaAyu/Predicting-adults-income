# Predicting-adults-income

Didactic purpose of the project:
* To encode categorical data for use with machine learning algorithms;
* To understand random forest learning algorithms for classification;
* To continue the investigations of overfitting.
* To learn to interpret a model by looking at feature importance scores.
Problem description 
We'll use the famous Adult dataset. This is a binary classification task, where our task is to predict whether an American individual earns more than $50,000 a year, given a number of numerical and categorical features. (The dataset was extracted from a 1994 census database.) 

# Project Task 1: 
This project deals with a dataset that has categorical features. 
Main steps:
* Step 1. Reading the data
* Step 2: Encoding the features as numbers: the file contains many categorical values so the categorical features will be transformed to numerical ones. We define one new column for each observed value of the feature.
* Step 3. Combining the steps. We used the pipeline to integrate the vectorization and classification functions by applying make_pipeline function.
Task 2: Decision trees and random forests
* Underfitting and overfitting in decision tree classifiers
* Underfitting and overfitting in random forest classifiers
Task 3: Feature importance in random forest classifiers
Decision trees and random forests are trained by computing importance scores for individual features in different ways: information gain, Gini impurity, variance reduction, etc.

