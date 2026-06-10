# Aviation Accident Analysis and Forecasting

## Project Overview

This project analyzes historical aviation accident records to identify factors associated with fatal injuries and forecast future aviation fatality trends. Using machine learning regression models and time-series forecasting techniques, the project aims to provide insights into aviation safety and accident outcomes.

The study leverages accident, aircraft, operational, and environmental information to understand the factors that contribute to fatalities and to estimate future fatality patterns.

---

## Problem Statement

Aviation accidents continue to be a major concern for aviation authorities, airlines, manufacturers, and safety investigators. Understanding the factors that influence accident fatalities and anticipating future fatality trends can support data-driven safety improvements.

This project seeks to answer the following questions:

- Which factors contribute most to aviation fatalities?
- Can machine learning models predict the number of fatal injuries in an accident?
- How have aviation fatalities changed over time?
- Can future fatality trends be forecast using historical accident data?

---

## Project Objectives

### Main Objective

To analyze aviation accident data and develop machine learning and forecasting models that predict aviation fatalities and forecast future fatality trends.

### Specific Objectives

- Explore and understand historical aviation accident data.
- Identify patterns and trends associated with fatal injuries.
- Analyze the impact of aircraft, weather, and operational factors on fatalities.
- Develop regression models for fatality prediction.
- Compare the performance of multiple machine learning algorithms.
- Forecast future aviation fatality trends using time-series models.
- Generate insights that support aviation safety analysis.

---

## Dataset

This project uses aviation accident records containing information such as:

- Aircraft manufacturer
- Aircraft model
- Aircraft category
- Engine type
- Weather conditions
- Flight phase
- Aircraft damage
- Operational characteristics
- Fatal injuries
- Serious injuries
- Accident dates

### Primary Target Variable

**inj_tot_f** – Total Fatal Injuries

---

## Machine Learning Task

### Regression

The regression component predicts the number of fatal injuries resulting from an aviation accident.

### Models

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- TensorFlow MLP Regressor

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Time-Series Forecasting

The forecasting component analyzes fatal injury trends over time and predicts future fatality patterns.

### Forecasting Models

- ARIMA
- SARIMA
- Prophet
- LSTM (Optional)

### Evaluation Metrics

- MAE
- RMSE
- MAPE

---

## Exploratory Data Analysis

The project investigates:

- Fatal injuries by aircraft manufacturer
- Fatal injuries by aircraft model
- Fatal injuries by weather condition
- Fatal injuries by flight phase
- Fatal injuries by aircraft damage level
- Fatality trends over time
- Seasonal accident patterns
- Correlation analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow
- Statsmodels
- Prophet
- Jupyter Notebook

---

## Project Structure

```text
Aviation-accident-analysis-forecasting/
│
├── data/
│   └── merged_air_crash_data.csv
│
├── notebooks/
│   └── Aviation_Accident_Analysis_and_Forecasting.ipynb
│
├── images/
│   └── visualizations/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## Expected Outcomes

- Identification of key factors associated with aviation fatalities.
- Accurate regression models for fatality prediction.
- Forecasts of future aviation fatality trends.
- Actionable aviation safety insights based on historical accident data.

---

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modeling
- Neural Networks with TensorFlow
- Time-Series Forecasting
- Model Evaluation and Comparison
- Data Visualization
- Aviation Safety Analytics

---

## Author

**June Konuche**

BSc Mathematics and Computer Science

Data Science | Machine Learning | Aviation Analytics
