# Digit Recognition Pipeline

This project focuses on building a pipeline for digit recognition using various machine learning algorithms. It involves data preprocessing, model selection, training, and evaluation.

## Overview

The project performs the following steps:

1. **Importing Libraries and Loading Data**:
   - Imports necessary libraries such as scikit-learn, Matplotlib, and Seaborn.
   - Loads the Digits dataset, which consists of images of handwritten digits.

2. **Data Exploration and Visualization**:
   - Checks the keys and shape of the dataset.
   - Visualizes some sample images from the dataset.

3. **Data Preprocessing and Splitting**:
   - Splits the dataset into features (X) and target variable (y).
   - Splits the data into training and testing sets.

4. **Model Selection and Training**:
   - Creates a pipeline with standard scaling and different classifiers (Logistic Regression, Random Forest, SVM).
   - Performs cross-validation to select the best model based on accuracy.

5. **Model Evaluation**:
   - Trains the best model on the training data.
   - Evaluates the model on the testing data using accuracy, classification report, and confusion matrix.
