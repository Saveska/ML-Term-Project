## Letter Recognition Classification

## Overview
This project focuses on classifying a large number of black-and-white rectangular pixel displays into the 26 capital letters of the English alphabet. It utilizes machine learning techniques to identify these letters from a dataset obtained from the UCI Machine Learning Repository.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Feature Selection](#feature-selection)
- [Basis Function Expansion](#basis-function-expansion)
- [Feature Extraction](#feature-extraction)
- [Data Visualization](#data-visualization)
- [Classification Models](#classification-models)
- [Support Vector Machines (SVM)](#support-vector-machines-(svm))
- [Neural Networks](#neural-networks)
- [XGBoost](#xgboost)
- [Random Forest](#random-forest)
- [Evaluation Scores](#evaluation-scores)

## Data

The dataset used for this project contains information about black-and-white rectangular pixel displays, with each display corresponding to one of the 26 capital letters of the English alphabet. The dataset includes features such as the dimensions and various pixel-related attributes.

## Feature Selection

The project begins by loading the dataset and performing feature selection to identify the relevant features. The dataset is then split into training and testing sets for further analysis.

## Basis Function Expansion

Polynomial features are created up to the second degree, providing an expanded feature space for modeling. However, for model training, the original dataset is used to avoid high dimensionality issues.

## Feature Extraction

Feature extraction is performed using t-SNE (t-Distributed Stochastic Neighbor Embedding) to visualize the data in a two-dimensional space. Label encoding is applied to make the data numerical before t-SNE transformation.

## Data Visualization

Data visualization includes a t-SNE plot that visualizes the transformed data points with different colors representing the 26 capital letters. Additionally, a pairplot is generated to visualize relationships between variables in the dataset.

## Classification Models

### Support Vector Machines (SVM)

Support Vector Machines (SVM) are employed for classification. The SVM classifier maximizes the margin between different classes of data points. The default "rbf" kernel is used for non-linear classification.

### Neural Networks

A Multi-layer Perceptron (MLP) neural network is trained for classification. Default hyperparameter values are used.

### XGBoost

XGBoost, an ensemble learning algorithm, is employed. It iteratively generates decision trees to improve classification accuracy.

### Random Forest

Random Forest, another ensemble learning algorithm, is used. It works in parallel, and multiple decision trees are combined for classification.

## Evaluation Scores

The project evaluates the classification models using several metrics, including accuracy, precision, and recall. These metrics provide insights into the models' performance in classifying the black-and-white rectangular pixel displays into the 26 capital letters.

According to these metrics, the results suggest that the models have performed well in achieving the project's objective of identifying the English capital letters from the dataset.
