# Data Classification Using AI

This repository contains **Project 2: Data Classification Using AI**, completed as part of the Artificial Intelligence Internship at DecodeLabs.

## Overview

The objective of this project is to build a basic machine learning classification model using the Iris dataset.

The Iris dataset contains flower measurements that are used to classify samples into three species:

- Setosa
- Versicolor
- Virginica

## Workflow

The project follows a basic machine learning pipeline:

1. Load and understand the Iris dataset
2. Split the dataset into training and testing sets
3. Apply feature scaling using StandardScaler
4. Train a K-Nearest Neighbors (KNN) classification model
5. Make predictions on the test data
6. Evaluate the model performance
7. Predict the class of a new flower sample

## Model

**Algorithm:** K-Nearest Neighbors (KNN)

**Train-Test Split:** 80% Training / 20% Testing

**Feature Scaling:** StandardScaler

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Result

The model achieved an accuracy of approximately **93.33%** on the test dataset.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

## Project Structure

```text
Ai_internship_task_2/
│
├── iris_classification.ipynb
└── README.md
