# Breast Cancer Detection Using Logistic Regression

This repository contains a Jupyter notebook that demonstrates the application of Logistic Regression to detect breast cancer based on various cell nucleus features.

## Dataset Overview

The dataset used in this project contains the following features:
- **radius_mean**: Mean of distances from center to points on the perimeter
- **texture_mean**: Standard deviation of gray-scale values
- **perimeter_mean**
- **area_mean**
- **smoothness_mean**: Local variation in radius lengths
- **compactness_mean**: Perimeter^2 / area - 1.0
- **concavity_mean**: Severity of concave portions of the contour
- **concave points_mean**: Number of concave portions of the contour
- ... and other similar features.

The target variable is:
- **diagnosis**: Indicates whether the cancer is malignant (M) or benign (B), encoded as 1 for malignant and 0 for benign.

## Project Overview

The project is divided into the following steps:

1. **Data Loading and Exploration**: 
   - Importing necessary libraries such as `pandas` and `seaborn`.
   - Loading the dataset and performing an initial exploration to understand its structure and identify any missing values.
   
2. **Data Preprocessing**:
   - Dropping unnecessary columns and handling missing values.
   - Converting the categorical `diagnosis` column into numeric form.
   
3. **Feature Scaling**:
   - Applying `StandardScaler` to normalize the feature set to bring all features onto a common scale.

4. **Model Building**:
   - Splitting the dataset into training and testing sets.
   - Fitting a Logistic Regression model to the training data.
   - Making predictions on the test data.

5. **Model Evaluation**:
   - Evaluating the model's performance using accuracy, precision, recall, and F1-score.

## How to Use

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/breast-cancer-detection-logistic-regression.git
