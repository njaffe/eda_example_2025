# Housing Data Analysis and Model Comparison

This repository contains a series of Jupyter notebooks that demonstrate the process of analyzing a housing dataset and comparing various machine learning models for predicting housing prices. The analysis is broken down into distinct steps to ensure modularity and easy understanding of each stage of the process.

## Project Structure

The project consists of the following notebooks and files:

### Notebooks:

- 1_data_loading_preprocessing.ipynb
    - Loads the housing dataset and performs initial data preprocessing steps. This includes handling missing values, encoding categorical variables, and saving the cleaned data for further use.

- 2_modeling-linreg.ipynb
    - Implements a simple linear regression model on the processed dataset. The model is trained and evaluated with performance metrics such as Mean Squared Error (MSE).

- 3_modeling-quad_factor.ipynb
    - Extends the modeling approach by adding quadratic features to the dataset and fitting a quadratic regression model to improve performance.

- 4_modeling-regularization.ipynb
    - Applies regularization techniques such as Lasso and Ridge regression to prevent overfitting and improve model generalization.

- 5_compare_to_other_models.ipynb
    - Compares the performance of the linear, quadratic, and regularized models to other machine learning models, such as decision trees and random forests.

- 6_compare_model_performance.ipynb
    - Evaluates and compares the performance of all models based on metrics like R-squared, MSE, and visualization of prediction errors.

### Other Files:

- data/
    - The folder contains the raw dataset used for the analysis. It should be referenced for loading data in the relevant notebooks.