Crop Recommendation System Using Machine Learning
Overview
This project aims to develop a Crop Recommendation System that assists farmers in selecting the most suitable crop to grow based on specific environmental and soil conditions. The system uses historical data and machine learning techniques to make accurate and data-driven crop recommendations.

Objectives
Primary Objective: To predict the most suitable crop based on user-provided inputs, including soil nutrients, temperature, humidity, pH, rainfall, and location (state).
Secondary Objective: To create an interactive system that provides real-time crop recommendations.
Dataset
The dataset includes the following features:

Soil Nutrients: Nitrogen (N_SOIL), Phosphorus (P_SOIL), Potassium (K_SOIL)
Climate Conditions: Temperature, Humidity, Rainfall
Soil pH: pH level of the soil
Location: State (geographical location)
Target: The crop historically grown under similar conditions.
Methodology
Data Preprocessing:

Encoding categorical variables using LabelEncoder.
Standardizing features with StandardScaler.
Model Building:

Model: RandomForestClassifier is used for training.
Evaluation: Accuracy, precision, recall, and F1-score metrics.
Custom Input Prediction:

Users input soil and climate conditions.
The model predicts and outputs the recommended crop.
Visualization:

Confusion matrix heatmap to visualize prediction accuracy.
Implementation Details
Language: Python
Libraries:
pandas for data handling.
scikit-learn for machine learning.
seaborn, matplotlib for visualization.
Model: Random Forest Classifier
