# Regression and Classification on the Pima Indians Diabetes Dataset

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)](https://numpy.org/)
[![Machine Learning](https://img.shields.io/badge/Task-Machine%20Learning-green)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Project Overview

This project demonstrates an end-to-end supervised machine learning workflow using the Pima Indians Diabetes Dataset.

Two machine learning tasks are implemented:

### Regression

Predicting a patient's BMI using clinical and demographic features.

### Classification

Predicting whether a patient has diabetes using clinical and demographic features.

## Dataset

The dataset contains medical and demographic information about patients, including:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome

## Regression

### Target

BMI

### Features

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* DiabetesPedigreeFunction
* Age

### Evaluation Metrics

* MAE
* MSE
* RMSE
* R²

## Classification

### Target

Outcome

* 0 = No Diabetes
* 1 = Diabetes

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

## Preprocessing

The project includes:

* Data inspection
* Handling invalid zero values
* Missing-value treatment
* Train-test splitting
* Feature scaling
* Model training
* Prediction
* Model evaluation
* Visualization

## Models

### Regression

Linear Regression

### Classification

Logistic Regression

## Project Structure

```text
pima-diabetes-ml/
│
├── Pima_Diabetes_Regression_Classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```
