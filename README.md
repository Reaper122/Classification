# Lung Cancer Prediction using K-Nearest Neighbors

This repository contains a Python script that uses the K-Nearest Neighbors (KNN) algorithm to predict lung cancer based on a given dataset.

## Dependencies

The script requires the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib

## Dataset

The dataset used in this script is a CSV file named "survey lung cancer.csv". This file should be located in the same directory as the script.

## Features

The script performs the following operations:

1. **Data Loading**: Loads the lung cancer survey data from a CSV file.
2. **Data Exploration**: Explores the data by displaying the first few rows, the shape of the dataset, and basic statistical details.
3. **Data Preprocessing**: Performs label encoding and drops unnecessary columns.
4. **Data Visualization**: Plots the standard deviation of features and a heatmap of feature correlations.
5. **Model Training**: Splits the data into training and testing sets, and trains a KNN model. The number of neighbors is determined by cross-validation for values from 1 to 15.
6. **Model Evaluation**: Evaluates the model using a confusion matrix and classification report.

## Usage

To run the script, use a Jupyter notebook or any Python environment that supports inline plotting with matplotlib. Simply import the script and run it.

## Results

The script outputs the accuracy of the KNN model for different numbers of neighbors, and displays a plot of these accuracies. It also outputs a confusion matrix and classification report for the model with the optimal number of neighbors.
