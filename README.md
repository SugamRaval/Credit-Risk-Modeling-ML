# Credit-Risk-Modeling-ML

## Overview

This project implements a credit risk assessment system using machine learning techniques. It leverages data from two separate Excel files and combines them to create a comprehensive dataset for analysis. The system includes data preprocessing steps, feature selection techniques, model fitting using random forest, XGBoost, and decision tree classifiers, hyperparameter tuning, and evaluation metrics computation.

## Steps

1. **Data Loading and Preprocessing:**
   - Load data from Excel files (`load_data.py`).
   - Remove null values and columns with a significant number of missing values.

2. **Feature Selection:**
   - Perform feature selection using chi-square test and variance inflation factor (VIF) (`feature_selection.py`).
   - Determine significant categorical and numerical features for model fitting.

3. **Model Fitting and Evaluation:**
   - Utilize machine learning classifiers such as random forest, XGBoost, and decision tree (`model_fitting.py`).
   - Fit models on the selected features and evaluate their performance using accuracy, precision, recall, and F1-score.

4. **Hyperparameter Tuning:**
   - Perform hyperparameter tuning for the XGBoost classifier to optimize model performance (`hyperparameter_tuning.py`).
   - Evaluate various combinations of hyperparameters using grid search and cross-validation.

5. **Main Script Execution:**
   - Execute the entire pipeline by orchestrating data loading, feature selection, model fitting, and hyperparameter tuning (`main.py`).

## Usage

To use the system:

1. Ensure that the necessary Python libraries are installed, as listed in the `requirements.txt` file.
2. Run the `main.py` script to execute the entire pipeline.
3. Review the evaluation metrics printed in the console to assess model performance.
4. Optionally, explore further improvements through hyperparameter tuning.

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
```
## Requirements

The project requires the following dependencies:

- NumPy
- pandas
- Matplotlib
- scikit-learn
- SciPy
- Statsmodels
- XGBoost
