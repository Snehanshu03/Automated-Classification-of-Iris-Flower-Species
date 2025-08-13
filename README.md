# Automated-Classification-of-Iris-Flower-Species



This project demonstrates how to use a Decision Tree Classifier to predict the species of Iris flowers based on their measurements.

## Project Overview

The goal of this project is to build a machine learning model that can accurately classify Iris flowers into one of three species: setosa, versicolor, or virginica, using the well-known Iris dataset.

The workflow includes:

1.  **Loading the Dataset**: The Iris dataset, which is included in the scikit-learn library, is loaded.
2.  **Data Preparation**: The data is split into features (measurements) and the target (species). The target variable is mapped from numerical representation to actual species names for better readability.
3.  **Data Splitting**: The dataset is divided into training and testing sets to train and evaluate the model.
4.  **Model Training**: A Decision Tree Classifier is trained on the training data.
5.  **Model Evaluation**: The trained model is evaluated on the test data using accuracy and a classification report.
6.  **Prediction**: The model is used to predict the species of a new, unseen Iris flower based on its measurements.

## Requirements

*   Python 3.6+
*   scikit-learn
*   pandas

These libraries can be installed using pip:
python your_script_name.py
