# Heart Disease Prediction using Logistic Regression

This repository contains the code and data to build a logistic regression model for predicting the risk of heart disease based on personal key indicators. The dataset used for this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease).

## Introduction

Heart disease is a leading cause of death worldwide, and early detection and prediction of heart disease risk can be crucial for preventive healthcare measures. This project aims to develop a logistic regression model that predicts the likelihood of heart disease based on several key indicators such as age, cholesterol levels, blood pressure, etc.

## Dataset

The dataset used for this project is provided by Kaggle and contains various personal key indicators of heart disease. It consists of the following columns:

- `age`: Age of the patient
- `sex`: Gender of the patient (0: female, 1: male)
- `chest_pain_type`: Type of chest pain experienced by the patient (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic)
- `resting_blood_pressure`: Resting blood pressure (mm Hg) of the patient
- `cholesterol`: Serum cholesterol level (mg/dl) of the patient
- `fasting_blood_sugar`: Fasting blood sugar (> 120 mg/dl, 0: false, 1: true)
- `resting_ecg`: Resting electrocardiographic results (0: normal, 1: having ST-T wave abnormality, 2: showing probable or definite left ventricular hypertrophy)
- `max_heart_rate`: Maximum heart rate achieved during exercise
- `exercise_induced_angina`: Exercise-induced angina (0: no, 1: yes)
- `st_depression`: ST depression induced by exercise relative to rest
- `st_slope`: Slope of the peak exercise ST segment (1: upsloping, 2: flat, 3: downsloping)
- `num_major_vessels`: Number of major vessels colored by fluoroscopy (0-3)
- `thalassemia`: Thalassemia type (3: normal, 6: fixed defect, 7: reversable defect)
- `heart_disease`: Target variable (0: absence, 1: presence of heart disease)
