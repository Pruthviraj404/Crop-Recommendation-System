# Crop Recommendation System Using Machine Learning

## Overview

This project develops a **Crop Recommendation System** to assist farmers in choosing the most suitable crop to grow based on specific environmental and soil conditions. Leveraging historical data and machine learning, the system provides accurate and data-driven crop recommendations.

## Objectives

- **Primary Objective**: Predict the most suitable crop based on user-provided inputs such as soil nutrients, temperature, humidity, pH, rainfall, and geographical location (state).
- **Secondary Objective**: Create an interactive system that offers real-time crop recommendations.

## Dataset

The dataset includes various features relevant to agriculture:
- **Soil Nutrients**:
  - Nitrogen (N_SOIL)
  - Phosphorus (P_SOIL)
  - Potassium (K_SOIL)
- **Climate Conditions**:
  - Temperature
  - Humidity
  - Rainfall
- **Soil pH**: pH level of the soil
- **Location**: State (geographical location within the country)
- **Target**: The crop that was historically grown under similar conditions.

## Methodology

### 1. Data Preprocessing
- **Handling Missing Values**: Ensuring data integrity.
- **Encoding Categorical Variables**: Using `LabelEncoder` for the `STATE` and `CROP` features.
- **Feature Scaling**: Standardizing features using `StandardScaler`.

### 2. Model Building
- **Model Selection**: `RandomForestClassifier` chosen for its robustness.
- **Training**: The model is trained to learn the relationship between environmental conditions and crop types.
- **Evaluation**: Model performance evaluated using accuracy, precision, recall, and F1-score metrics.

### 3. Custom Input Prediction
- **User Interaction**: The system accepts custom inputs from the user for soil and climate conditions.
- **Prediction**: The trained model predicts the most suitable crop based on these inputs.
- **Output**: The predicted crop is displayed to the user.

### 4. Visualization
- **Confusion Matrix**: A heatmap is used to visualize the model’s performance.

## Implementation Details

- **Programming Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `scikit-learn`: For machine learning model building and evaluation.
  - `seaborn` & `matplotlib`: For data visualization.
- **Model**: Random Forest Classifier
- **Feature Scaling**: `StandardScaler` for feature normalization.
- **Label Encoding**: `LabelEncoder` for categorical variables.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/crop-recommendation-system.git
