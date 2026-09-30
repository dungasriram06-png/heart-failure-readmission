# heart-failure-readmission
Machine learning project for predicting 30-day heart failure readmission using patient healthcare data.
## Project Overview

This project focuses on predicting 30-day hospital readmission among patients with heart failure using machine learning techniques.

The goal is to analyze patient healthcare data, preprocess the data, train multiple binary classification models, and evaluate their performance using appropriate classification metrics.

## Problem Statement

Hospitals need to identify patients who may be at higher risk of readmission after a heart-failure-related hospitalization. Early identification can support follow-up planning, discharge management, and post-discharge care.

This project develops machine learning models to predict whether a patient will be readmitted within 30 days.

## Objectives

- Explore and understand the heart failure readmission dataset.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA).
- Train multiple binary classification models.
- Perform hyperparameter tuning.
- Evaluate model performance using classification metrics.
- Compare the final tuned models using ROC-AUC and other evaluation metrics.

## Dataset

The dataset contains patient-level healthcare information related to heart failure and hospital readmission.

The target variable represents whether the patient was readmitted within 30 days.

The dataset used in this project is available in the `dataset/` folder.

## Machine Learning Models

The project evaluates three binary classification approaches:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)

Hyperparameter tuning and model evaluation were performed to obtain the final model configurations.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Cross-validation was also used to assess model performance and stability.

## Project Structure

```text
heart-failure-readmission/
│
├── dataset/
│   └── dataset_12000_records.csv
│
├── notebook/
│   └── Month_1_Heart_Failure_Readmission.ipynb
│
├── report/
│   └── Heart_Failure_Readmission_Report.pdf
│
└── README.md
