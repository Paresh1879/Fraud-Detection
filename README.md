# Fraud Detection Team Data Detective

## Overview

This repository contains a Jupyter Notebook for analyzing credit card transactions data and building models for fraud detection.

## Key Features

1. **Data Preprocessing**:
   - Handles missing values
   - Performs one-hot encoding on categorical features
   - Ensures data integrity and compatibility with classification algorithms

2. **Model Evaluation for Classification**:
   - Evaluates the performance of various classification models (Logistic Regression, Decision Tree Classifier, Random Forest Classifier)
   - Computes the mean accuracy score and standard deviation for each classifier
   - Assesses the accuracy of the Logistic Regression model using classification reports

3. **Data Preprocessing for Regression**:
   - Splits the data into features and target variables
   - Further divides the data into training and test sets

4. **Model Evaluation for Regression**:
   - Defines preprocessing steps and pipelines for regression models (Linear Regression, Random Forest Regressor, Gradient Boosting Regressor)
   - Trains each model, predicts on the test data, and calculates the Root Mean Squared Error (RMSE)
   - Provides a comparative view of model performance

5. **Hyperparameter Tuning for Regression**:
   - Tunes the hyperparameters of the Random Forest Regressor model using Grid Search Cross-Validation
   - Finds the optimal hyperparameter values that minimize the RMSE on the validation set
   - Creates a final model with the optimal hyperparameters and evaluates it on the test set

## Dependencies

The notebook requires the following Python libraries:

- `pandas`
- `matplotlib`
- `scikit-learn`
- `imbalanced-learn`
- `numpy`
- `scipy`
- `joblib`
- `threadpoolctl`

These libraries can be installed using `pip` or `conda`.

## Usage

1. Ensure that you have the required dependencies installed.
2. Run the Jupyter Notebook to execute the provided code and explore the fraud detection analysis.
3. The notebook includes several functions that can be used for data preprocessing, visualization, and modeling. You can modify or extend these functions as needed for your specific analysis requirements.

## Data Source

The credit card transactions dataset is provided in the `data` directory, with separate files for each chapter of the analysis.

## Future Improvements

- Implement the modeling tasks and evaluate the performance of different models.
- Expand the analysis to include more insights and findings from the credit card transactions data.
- Incorporate additional data sources or features to enhance the fraud detection capabilities.
- Add more detailed comments and documentation to improve the code's readability and maintainability.



