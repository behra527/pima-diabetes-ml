# Regression and Classification on the Pima Indians Diabetes Dataset

## Project Overview

This project demonstrates an end-to-end supervised machine learning workflow using the Pima Indians Diabetes Dataset.

Two machine learning tasks are implemented:

### Regression

Predicting a patient's BMI using clinical and demographic features.

### Classification

Predicting whether a patient has diabetes using clinical and demographic features.

## Dataset

The dataset contains medical and demographic information about patients, including:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

## Regression

### Target

BMI

### Features

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- DiabetesPedigreeFunction
- Age

### Evaluation Metrics

- MAE
- MSE
- RMSE
- R²

## Classification

### Target

Outcome

- 0 = No Diabetes
- 1 = Diabetes

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Preprocessing

The project includes:

- Data inspection
- Handling invalid zero values
- Missing-value treatment
- Train-test splitting
- Feature scaling
- Model training
- Prediction
- Model evaluation
- Visualization

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
<<<<<<< HEAD
└── .gitignore
=======
└── .gitignore
>>>>>>> 6f4b654e285457f91288af1dd8a4814edd3ffbcf
