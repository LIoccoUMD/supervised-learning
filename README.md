# Supervised Learning Project

This repository contains code for a supervised learning project aimed at predicting student GPA using various machine learning algorithms. Here's an overview:

## Project Overview

- **Objective**: Predict student GPA based on multiple features using different regression models.
- **Algorithms Used**:
  - **Linear Regression**: Used to establish a baseline performance by fitting a linear equation to the observed data.
  - **Random Forest Regression**: Applied to capture non-linear relationships, providing an ensemble learning method to improve prediction accuracy.
  - **K-Nearest Neighbors (KNN) Regression**: Employed to predict values based on the average of the 'k' closest data points in the feature space.

## Methodology

- **Data Preparation**: Selected features from dataset, excluding 'id' and 'gpa' for training.
- **Model Training and Testing**: Each model was trained on 80% of the data with the remaining 20% reserved for testing.
- **Model Evaluation**: Performance assessed using Mean Squared Error (MSE).

## Usage

To run this project:
- Download the dataset listed at the top of the .ipynb file
- Make sure it is in a reachable location

```bash
git clone https://github.com/LIoccoUMD/supervised-learning/
cd supervised-learning
python Supervised_Learning.ipynb

## OR, for an easier setup
- Open in Google Colab
- Download the linked dataset
- Run directly in Colab
