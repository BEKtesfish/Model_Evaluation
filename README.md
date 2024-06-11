## Machine Learning Model Evaluation

  This repository contains code for evaluating different machine learning models: linear regression, binary classification neural networks, and neural networks. 
  Each file contains Python code demonstrating how to build, train, and evaluate the respective model.

## Files:

### linear_regression_evaluation.py: 
  This file demonstrates how to perform linear regression evaluation. It includes steps for data loading, preprocessing, model training, and evaluation using both 
  scikit-learn utilities and custom implementation. It also explores the addition of polynomial features to improve model performance.

### bc_nn_evaluation.py: 
  This file contains code for evaluating three binary classification neural network models. It demonstrates how to load data, preprocess features, build multiple    neural network architectures, train the models, and evaluate their performance on training, cross-validation, and test sets.

### nn_evaluation.py: 
  This file showcases the evaluation of neural network models. It covers data loading, feature scaling, model building, training, and evaluation using mean 
  squared error (MSE) metrics on both training and cross-validation sets. It also selects the best-performing model based on cross-validation MSE and evaluates 
  its performance on the test set.

## Usage:
  To run each file, ensure you have the necessary dependencies installed:

    pip install numpy matplotlib scikit-learn tensorflow

 Then, execute each Python script using a Python interpreter:

    python linear_regression_evaluation.py
    python bc_nn_evaluation.py
    python nn_evaluation.py


