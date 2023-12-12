# HealthCost Predictive Analysis

## Overview
HealthCost Predictive Analysis is a comprehensive project aimed at exploring, analyzing, and predicting healthcare insurance costs using various machine learning models. The project utilizes a rich dataset that includes variables such as age, sex, BMI, number of children, smoker status, region, and insurance charges.

## Project Structure
1. `Healthcare_Costs_Data_Analysis.ipynb` - This Jupyter notebook focuses on the initial data analysis, including data cleaning, exploration, and visualization.
2. `Healthcare_Costs_Prediction_Models.ipynb` - This notebook contains the implementation of multiple machine learning models for predicting healthcare costs, along with model evaluation and selection.

## Dataset
The dataset, `insurance.csv`, includes the following columns:
- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges

## Data Analysis and Visualization
The data analysis phase includes:
- Checking for missing values and duplicates.
- Statistical summary of the data.
- Visualization of different variables using plots like count plots, scatter plots, and distribution plots.

## Predictive Modeling
Several regression models have been implemented to predict insurance charges:
- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regression

The models are evaluated based on metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Grid Search CV is used for hyperparameter tuning in SVR and Random Forest models.

## Requirements
- Python 3
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn

## Installation
Clone this repository and install the required Python packages.

```bash
git clone https://github.com/DavidTkeshelashvili/HealthCost-Predictive-Analysis
pip install -r requirements.txt
