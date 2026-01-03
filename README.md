# Breast Cancer Prediction using Logistic Regression

This project implements a machine learning model to predict breast cancer (malignant or benign) using the Logistic Regression algorithm. The dataset utilized is the Breast Cancer Wisconsin (Diagnostic) dataset from `sklearn.datasets`.

## Project Overview

The goal of this project is to build a predictive system that can classify a tumor as either benign (non-cancerous) or malignant (cancerous) based on various features derived from cell nuclei. 

## Key Steps:

1.  **Data Collection and Processing**: 
    *   Loading the Breast Cancer Wisconsin dataset from `sklearn`. 
    *   Converting the dataset into a Pandas DataFrame for easier manipulation. 
    *   Performing Exploratory Data Analysis (EDA) including checking for missing values, understanding data distribution, and basic statistical measures. 
    *   Separating features (input variables) from the target variable (label).

2.  **Data Splitting**: 
    *   Dividing the dataset into training and testing sets to evaluate the model's performance on unseen data. A `test_size` of 0.2 (20%) is used, with a `random_state` for reproducibility.

3.  **Model Training**: 
    *   Implementing a Logistic Regression model, a widely used algorithm for binary classification problems. 
    *   Training the model on the `x_train` and `y_train` data.

4.  **Model Evaluation**: 
    *   Assessing the model's performance using accuracy scores on both the training and testing datasets. This helps in understanding how well the model generalizes.

5.  **Building a Predictive System**: 
    *   Developing a function to take new input data (features of a tumor) and predict whether the tumor is malignant or benign. 
    *   The system takes numerical input, converts it into a NumPy array, reshapes it, and then uses the trained Logistic Regression model to make a prediction.

## Technologies Used:

*   Python
*   `pandas` for data manipulation
*   `numpy` for numerical operations
*   `sklearn` for dataset loading, model selection, Logistic Regression, and accuracy metrics.

## How to Use:

To run this project, execute the cells in the provided Jupyter/Colab notebook sequentially. The notebook will guide you through data loading, preprocessing, model training, evaluation, and demonstrates how to use the predictive system.
