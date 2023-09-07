# Student Score Prediction

This repository contains a Jupyter Notebook demonstrating a supervised machine-learning task using Python and Scikit-Learn. The task involves predicting student scores based on the number of hours they studied.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Loading](#data-loading)
- [Data Visualization](#data-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Custom Prediction](#custom-prediction)
- [Conclusion](#conclusion)

## Introduction

This project uses supervised machine learning techniques to predict students' scores based on the number of hours they have studied. The code is implemented in Python and utilizes popular libraries such as NumPy, pandas, and Scikit-Learn.

## Getting Started

To run this project, you can use a Jupyter Notebook environment. The notebook is self-contained and can be executed cell by cell. The code is also hosted on Google Colab, making it easy to run and experiment with. You can access the original notebook at [this link](https://colab.research.google.com/drive/1zdMXN4ntAAMer2kQcfAr7JF6QAVozht1).

## Data Loading

The project starts by importing necessary libraries and loading the dataset from a remote URL using pandas. The dataset contains information about the number of hours students studied and their corresponding scores.

## Data Visualization

The dataset is visualized using Matplotlib to understand the relationship between hours studied and scores. A scatter plot is created to visualize the distribution of data points.

## Data Preprocessing

The data is split into independent and dependent variables. This step is essential for model training and testing. The dataset is divided into training and testing sets using Scikit-Learn's `train_test_split` function.

## Model Training

A linear regression model is created using Scikit-Learn's `LinearRegression` class. The model is trained on the training data to learn the relationship between hours studied and scores.

## Model Evaluation

The model's performance is evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE). These metrics measure the accuracy of the model's predictions compared to the actual scores.

## Custom Prediction

The model is used to predict scores based on a custom input (e.g., hours = 9.25). This demonstrates how the trained model can be applied to real-world scenarios.

## Conclusion

This project showcases a simple example of supervised machine learning, where a linear regression model is used to predict student scores based on the number of hours they studied. It provides an understanding of data preprocessing, model training, evaluation, and prediction. You can further explore and modify the code to apply similar techniques to other regression problems.
