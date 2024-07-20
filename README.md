## Start

# ACL Diagnosis Prediction with Decision Tree and Random Forest

## Overview

This project involves building machine learning models to predict the diagnosis of ACL (Anterior Cruciate Ligament) injuries based on sensor data. It includes models using both Decision Tree and Random Forest classifiers. The project categorizes the condition into three classes: "Healthy", "Fully Recovered", and "ACL Injured". It also evaluates and compares the performance of both models.

## Features

- **Model Training**: Trains Decision Tree and Random Forest classifiers using sensor data to predict ACL injury status.
- **Model Evaluation**: Evaluates model performance using accuracy, confusion matrix, and comparison between Decision Tree and Random Forest models.
- **Prediction**: Predicts ACL diagnosis based on new data input from CSV or Excel files.
- **Result Display**: Outputs predictions and saves results in a CSV file.

## Project Structure

- `data/`: Contains datasets for training and testing.
  - `ACL_Injury_Exercises.csv`: Contains some exercises for ACL-injured person
  - `carla_dataset.xlsx`: Contains a test dataset from IMU 6050 sensor
  - `metadata.csv`: Contains the dataset used for training and validating the model
  - `training_dataset.csv`: Contains the dataset for training the model
  - `validating_dataset.csv`: Contains the dataset for validating the model

- `models/`: Contains saved machine learning models.
  - `decision_tree.joblib`: Trained Decision Tree model.
  - `random_forest.joblib`: Trained Random Forest model.

- `results/`: Contains results and outputs of model predictions and evaluations.
  - `predicted_acl_diagnosis_random_forest.xlsx`: Contains results from the random_forest_algorithm
  - `predicted_acl_diagnosis_decision_tree.csv`: Contains results from the decision_tree_algorithm

- `codes/`: Contains scripts for training, evaluating, and predicting with models.
  - `Decision_tree_model.ipynb`: Script to train Decision Tree.
  - `random_forest_model.ipynb`: Script to predict ACL diagnosis from input file using the chosen model.
 

- `README.md`: This file.

## Requirements

- Python 3.x
- `pandas`: For data manipulation.
- `scikit-learn`: For machine learning.
- `joblib`: For saving and loading models.
- `matplotlib`: For plotting confusion matrices.
- `tabulate`: This is for displaying results in table format.

## The End
