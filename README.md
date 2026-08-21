# Boston Housing Regression with Perceptron

This project was developed as the first assignment of the Deep Learning course.

The goal is to predict house prices from the Boston Housing dataset using a simple Perceptron implemented in PyTorch.

## Dataset

The Boston Housing dataset contains 13 input features related to housing conditions. In this project, two features are used:

* `RM` — average number of rooms per dwelling
* `AGE` — proportion of older housing units

The dataset is divided into training, validation, and test sets. Data scaling is performed using `StandardScaler`, fitted only on the training set.

## Model

A single-layer Perceptron is used for the regression task. The model takes two input features and produces one output value representing the predicted house price.

## Evaluation

Model performance is evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

The test set is used only for the final evaluation.

## Visualization

The results include:

* Training and validation loss
* Actual vs. predicted values
* A 3D visualization of the data
* The predicted regression plane

## Tools

* Python
* PyTorch
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
