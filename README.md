# Predicting Hospitalization Complications Using Machine Learning

## Abstract

This project aims to develop a robust machine learning classifier to predict whether a patient will experience complications during hospitalization. We use a dataset containing various patient details and surgical timings to train and test multiple machine learning models, including Random Forest, XGBoost, and Neural Networks.

## Installation

The project uses the following Python libraries:
- pandas
- scikit-learn
- matplotlib
- seaborn
- XGBoost
- TensorFlow/Keras

To install all required packages, run:
```bash
pip install -r requirements.txt
```

## File Descriptions

- `SurgeryTiming.csv` - The dataset containing patient details and surgery timings.
- `Surgery Timing Data Dictionary.pdf` - Data dictionary explaining the variables in the dataset.
- `SurgeryTime-MLPredictor.ipynb` - Jupyter Notebook containing all the code and visualizations.

## How to Run

1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter Notebook.

## Data Cleaning and Preprocessing

Data cleaning steps included handling missing values and encoding categorical variables. Feature scaling was applied to normalize the dataset. Class imbalance was addressed by upsampling the minority class.

## Model Selection and Training

We selected Random Forest, XGBoost, and Neural Networks as the classifiers for this project. Hyperparameter tuning was performed using GridSearchCV for Random Forest and XGBoost. For Neural Networks, multiple architectures were tested.

## Results and Interpretation

- **Random Forest**: Accuracy of 94%, with high precision and recall.
- **XGBoost**: Accuracy of 95%, also with high precision and recall.
- **Neural Networks**: Accuracy of 93%, slightly lower but still competitive.

Various metrics like SHAP values and feature importances were used for model interpretability.