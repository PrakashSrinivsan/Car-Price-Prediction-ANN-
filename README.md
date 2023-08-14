# Car Price Prediction

Welcome to the **Car Price Prediction** project! This repository contains code and resources for predicting the total dollar amount that customers are willing to pay for a car based on various customer attributes. As a car salesman, developing an accurate price prediction model can enhance customer engagement and facilitate better decision-making.

## Project Overview

- **Author:** Prakash Srinivasan
- **Supervisor:** Professor Roberta Siciliano, University Of Naples Federico II

## Problem Statement

This project aims to develop a robust model that predicts the total dollar amount customers are willing to pay for a car. The prediction will be based on customer attributes, including customer information, country, gender, age, annual salary, credit card debt, and net worth. The goal is to provide car sales representatives with an accurate tool for estimating car purchase amounts.

## Table of Contents

1. **Exploratory Data Analysis**
   - Missing Value Detection
   - Data Normality Visualization
   - Outlier Detection with Box Plot
   - Correlation Analysis
   - Feature Importance with Random Forest and Lasso Regression

2. **Model Development**
   - Training and Evaluating the Model with Artificial Neural Networks (ANN)

## Exploratory Data Analysis

In this phase, we delve into the dataset to gain insights and prepare it for model training. Our analysis includes:

- **Missing Value Detection:** Identifying and handling missing values to ensure data completeness.
- **Data Normality Visualization:** Assessing the normality of data distributions through visualization techniques.
- **Outlier Detection with Box Plot:** Detecting outliers that could impact the model's performance using box plots.
- **Correlation Analysis:** Exploring relationships between attributes to understand potential influences on the target variable.
- **Feature Importance:** Determining feature importance using Random Forest and Lasso Regression to guide model training.

## Model Development

We train and evaluate our prediction model using Artificial Neural Networks (ANN). ANNs are known for capturing complex relationships in data and providing accurate predictions. After training, we assess the model's performance using evaluation metrics.

### Model Evaluation Results

- Mean Squared Error (MSE): 5.2961700098498004e-05
- R-squared (R2): 0.9987351720184348

These evaluation metrics demonstrate the high accuracy of our model in predicting car purchase amounts based on customer attributes.

## Usage Instructions

1. **Clone the Repository**: Begin by cloning this repository to your local machine using the following command:
   git clone https://github.com/PrakashSrinivsan/car-price-prediction.git
2. **Navigate to Project Directory**: Change your working directory to the project folder using:
   cd car-price-prediction
3. **Explore the Code**: Review the code and methodology used in the Colab Notebook. This notebook contains the EDA, model development, and evaluation steps.
4. **Install Dependencies**: If required, install the necessary Python dependencies using:
   pip install -r requirements.txt
5. **Run the Notebook**: Open the `Car Price Prediction.ipynb` notebook using Jupyter Notebook and execute the cells to reproduce the analysis and model training.

6. **Contribute**: If you identify ways to enhance the project or find any issues, consider forking the repository, making your modifications, and submitting a pull request.

## Contact

If you have any questions, suggestions, or feedback regarding this project, please feel free to contact the project author Prakash Srinivasan at psrinivasan028@gmail.com.

We appreciate your interest in our project and hope you find the insights and methodologies presented here valuable for your own research and projects.





