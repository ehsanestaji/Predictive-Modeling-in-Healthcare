# Hospital Complication Prediction

## Project Overview

This project aims to predict whether or not a patient will experience any complications during their hospital stay. The dataset includes various features like age, gender, BMI, and different health metrics. Multiple machine learning classifiers have been used and evaluated for this purpose.

## Data

The data for this project consists of over 14,000 records with 25 features, including the target variable 'complication'.

## Features

- `bmi`: Body Mass Index
- `Age`: Age of the patient
- `asa_status`: ASA Status
- `baseline_cancer`, `baseline_charlson`, `baseline_cvd`, etc.: Baseline health conditions
- `ahrq_ccs`: Procedure Category
- `ccsComplicationRate`, `ccsMort30Rate`: Complication and Mortality Rates
- `complication_rsi`, `mortality_rsi`: Risk Severity Indices
- `dow`: Day of the week
- `gender`: Gender of the patient
- `hour`, `month`: Timing of the surgery
- `moonphase`: Moon phase
- `mort30`: 30-day mortality
- `race`: Race of the patient
- `complication`: Target variable indicating if the patient experienced any complications

## Models Used

- Random Forest Classifier
- Support Vector Classifier
- Logistic Regression

### Advanced Techniques

- Hyperparameter tuning for Random Forest
- XGBoost

## Requirements

- Python 3.x
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- XGBoost

## How to Run

1. Clone this repository.
2. Install the required packages.
3. Run the Jupyter Notebook.

## Evaluation

The models are evaluated based on their accuracy, precision, recall, and F1-score. The Random Forest Classifier with hyperparameter tuning showed the best performance.

## Future Work

- Experiment with more advanced algorithms like neural networks.
- Apply more feature engineering techniques to improve the model's performance.
