# Heart Disease Prediction
This repository contains an analysis pipeline to predict heart disease occurrence based on health indicators. The project leverages machine learning classification models trained on the 2020 annual CDC survey data to provide predictions.

# Project Introduction
Heart disease is a leading cause of death in the U.S. This project aims to explore the correlation between coronary disease and health indicators, and develop a machine learning model to predict the likelihood of heart disease occurrence in patients. The model is trained using the CDC's Behavioral Risk Factor Surveillance System (BRFSS) data for 2020.

# Key Features
Explores patient health factors, demographic features, and underlying comorbidities.
Implements an array of machine learning models including logistic regression, random forest, k-nearest neighbors, and XGBoost.
Utilizes f-beta score as the evaluation metric, emphasizing on minimizing false negatives.
Provides comprehensive feature importance analysis.

# Repository Structure
notebooks/: Contains Jupyter notebooks of data exploration, modeling and evaluation.
data/: Contains the data used in the project.
results/: Contains the results of the models.
src/: Contains the Python scripts for data preprocessing, modeling, evaluation, and utility functions.

python: 3.10.5

pandas: 1.4.2

numpy: 1.22.4

matplotlib: 3.5.2

scikit-learn: 1.1.1

shap: 0.40.0
