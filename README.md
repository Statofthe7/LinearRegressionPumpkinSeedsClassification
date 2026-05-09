# Pumpkin Seeds Classification using Linear Regression

## Description
This program classifies pumpkin seed types using machine learning. The dataset contains various features of pumpkin seeds, which are used to train a linear regression model for classification.

## Dataset
The dataset used in this project is the 'Pumpkin Seeds Dataset' from KaggleHub. It contains 13 features describing pumpkin seeds and a 'Class' label indicating the seed type. Source: muratkokludataset/pumpkin-seeds-dataset

## Key Steps
1.  **Data Loading**: Downloading and loading the pumpkin seeds dataset.
2.  **Data Preprocessing**: Converting categorical seed types to numerical labels, and splitting the data into training and testing sets.
3.  **Model Training**: Training a Linear Regression model on the preprocessed data.
4.  **Model Evaluation**: Evaluating the model's performance using the R-squared score.

## Dependencies
-   `pandas`
-   `scikit-learn`
-   `kagglehub`

## Usage
To run this notebook, install the required libraries.

## Results
The linear regression model achieved an R-squared score of approximately 0.51, indicating a moderate fit to the data for predicting seed types based on the selected features.

