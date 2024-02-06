# Predicting Obesity using Deep Learning

This repository contains code for predicting obesity using deep learning techniques. This notebook is based on the "Playground Series - S4E2" Kaggle competition dataset. The code utilizes a dataset containing various features related to individuals' lifestyles and health habits to predict the likelihood of obesity.
Kaggle notebook link - https://www.kaggle.com/code/cheesecke/obesity-prediction-with-deep-neural-network
Dataset used - https://www.kaggle.com/competitions/playground-series-s4e2

## Overview

Obesity is a major public health concern worldwide, and accurate prediction of obesity risk can aid in preventive healthcare strategies. This project aims to develop a deep learning model capable of predicting obesity based on various lifestyle factors.

## Dataset

The dataset used in this project contains information about individuals' demographics, dietary habits, physical activity levels, and other lifestyle factors. It consists of two CSV files: `train.csv` for training the model and `test.csv` for evaluating the model's performance.

## Code Structure

- `obesity-prediction-with-deep-neural-network.ipynb`: Jupyter Notebook containing the code for data preprocessing, model building, training, evaluation, and prediction.
- `submission.csv`: CSV file containing the predicted labels for the test dataset, ready for submission.

2. Open and run the `predicting_obesity.ipynb` notebook in Jupyter or any compatible environment to execute the code step by step.

## Model Architecture

The deep learning model is built using TensorFlow and Keras. It consists of several dense layers with different activation functions, optimized using the Adam optimizer and trained using K-fold cross-validation.

## Evaluation

The model's performance is evaluated using various metrics such as accuracy, confusion matrix, classification report, and ROC curve.

## Results

The final predictions on the test dataset are saved in `submission.csv` for further analysis and submission.

## Contributing

Contributions to improve the code or add new features are welcome. Please create a new branch for your contributions and submit a pull request for review.
