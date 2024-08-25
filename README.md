# Heart-Disease-Prediction
This repository contains a machine learning model to predict the likelihood of heart disease using patient data. The model is built using Python and the scikit-learn library, employing Logistic Regression as the classifier.

# Introduction
Heart disease is one of the leading causes of death worldwide. The goal of this project is to predict the presence of heart disease in patients based on features such as age, sex, chest pain type, blood pressure, cholesterol level, and others. The model is trained on a dataset of patient information and uses logistic regression to classify whether a patient is likely to have heart disease.

# Dataset
The dataset used in this project is heart_disease_data.csv, which contains the following features:

- age: Age of the patient
- sex: Gender of the patient (1 = male, 0 = female)
- cp: Chest pain type (0-3)
- trestbps: Resting blood pressure
- chol: Cholesterol level
- fbs: Fasting blood sugar (1 if > 120 mg/dl, 0 otherwise)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise-induced angina (1 = yes, 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: The slope of the peak exercise ST segment
- ca: Number of major vessels colored by fluoroscopy
- thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
- target: Presence of heart disease (1 = yes, 0 = no)

# Model
The model is built using Logistic Regression from the scikit-learn library. Key steps include:

1. Data Collection and Preprocessing: Loading the dataset and handling missing data.
2. Model Training: Training a Logistic Regression model on the training data.
3. Evaluation: Evaluating the model performance using metrics such as accuracy.

# Results
The model's performance is evaluated based on accuracy. We can experiment with different algorithms and parameters to improve the results.
