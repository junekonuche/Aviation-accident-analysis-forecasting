# Aviation-accident-analysis-forecasting
An Advanced Machine Learning project that analyzes historical aviation accident data from the NTSB to identify accident patterns, predict accident severity, and forecast future aviation accident trends using machine learning and time-series forecasting models.




## Overview

Aviation safety remains a critical concern worldwide, making the analysis of accident patterns and trends essential for improving operational safety and risk management. This project applies machine learning and time-series forecasting techniques to historical aviation accident data from the National Transportation Safety Board (NTSB) to uncover accident patterns, predict accident severity, and forecast future accident trends.

The project combines exploratory data analysis, predictive modeling, and forecasting methods to generate actionable insights from aviation accident records.

---

## Problem Statement

Understanding the factors associated with aviation accidents is essential for improving safety and reducing future risks. However, the increasing volume of historical accident records makes manual analysis challenging.

This project aims to leverage machine learning and forecasting techniques to:

* Identify patterns and trends in aviation accident data.
* Predict accident severity using operational and environmental factors.
* Forecast future accident trends based on historical records.
* Generate insights that support aviation risk analysis and decision-making.

---

## Objectives

### Main Objectives

1. Analyze historical aviation accident records.
2. Identify key factors associated with accident severity.
3. Build classification models to predict accident severity.
4. Compare the performance of multiple machine learning models.
5. Forecast future aviation accident trends using time-series techniques.
6. Generate data-driven insights through visualizations and model interpretation.

---

## Dataset

This project uses the NTSB Aviation Accidents Dataset available on Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/mirzaniazmorshed/ntsb-aviation-accidents/data

Original Source:
National Transportation Safety Board (NTSB) Aviation Accident Database.

### Dataset Features

The dataset contains information related to:

* Aircraft manufacturer
* Aircraft model
* Aircraft category
* Weather conditions
* Flight phase
* Injury severity
* Aircraft damage level
* Accident location
* Accident date
* Flight operation details
* Probable causes

The dataset includes multiple related tables linked through a unique event identifier.

---

## Project Workflow

### 1. Data Collection

* Load aviation accident datasets.
* Merge relevant tables.
* Inspect data structure and quality.

### 2. Data Cleaning and Preprocessing

* Handle missing values.
* Remove duplicates.
* Encode categorical variables.
* Prepare features for machine learning models.

### 3. Exploratory Data Analysis (EDA)

* Accident distribution over time.
* Accident severity trends.
* Aircraft manufacturer analysis.
* Flight phase analysis.
* Weather condition analysis.
* Geographic accident patterns.

### 4. Feature Engineering

* Create derived features.
* Encode categorical variables.
* Select relevant predictors.

### 5. Classification Modeling

Build models to predict accident severity using:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

### 6. Time-Series Forecasting

Forecast future aviation accident trends using:

* ARIMA
* SARIMA
* Prophet

### 7. Model Evaluation

#### Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC

#### Forecasting Metrics

* MAE
* RMSE
* MAPE

### 8. Results and Insights

* Model comparison.
* Important risk factors.
* Accident trend forecasts.
* Aviation safety insights.

---

## Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn
* XGBoost

### Time-Series Forecasting

* Statsmodels
* Prophet

### Development Environment

* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Classification Modeling
* Ensemble Learning
* Hyperparameter Tuning
* Time-Series Forecasting
* Model Evaluation
* Data Visualization
* Model Interpretation

---

## Expected Outcomes

This project is expected to:

* Identify significant factors associated with aviation accident severity.
* Provide accurate accident severity predictions using machine learning models.
* Forecast future aviation accident trends using historical data.
* Generate insights that contribute to understanding aviation accident patterns.

---

## Repository Structure

aviation-accident-analysis-forecasting/

├── data/

│   ├── raw/

│   └── processed/

├── notebooks/

│   ├── 01_data_cleaning.ipynb

│   ├── 02_eda.ipynb

│   ├── 03_feature_engineering.ipynb

│   ├── 04_classification_models.ipynb

│   ├── 05_forecasting_models.ipynb

│   └── 06_model_evaluation.ipynb

├── reports/

│   ├── figures/

│   └── project_report.pdf

├── models/

├── README.md

└── requirements.txt

---

## Author

Advanced Machine Learning Capstone Project

Bachelor of Science in Mathematics and Computer Science
