# Telecom Churn Prediction Project

## Overview
This project aims to predict customer churn for a telecom company, focusing on high-value customers. We analyze customer behavior, build predictive models, and provide recommendations to reduce churn rate.

## Table of Contents
1. [Installation](#installation)
2. [Project Structure](#project-structure)
3. [Data](#data)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Recommendations](#recommendations)
7. [Future Work](#future-work)

## Installation
To run this project, you need Python 3.7+ and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Project Structure
- `telecom_churn_prediction.ipynb`: Main Jupyter notebook containing the analysis and models
- `data/`: Directory containing the dataset (not included in the repository)
- `images/`: Directory containing output images and plots
- `presentation.pdf`: Project presentation slides

## Data
The dataset contains customer-level information for a span of four consecutive months. It includes various features such as call details, recharge patterns, and internet usage.

## Methodology
1. Data Preprocessing
   - Filtering high-value customers
   - Handling missing values
   - Feature scaling
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Building
   - Logistic Regression
   - Random Forest
5. Handling Class Imbalance using SMOTE

## Results
- Random Forest model outperformed Logistic Regression
- Top churn predictors include:
  - Total outgoing and incoming minutes of usage in month 
  - Average Revenue Per User (ARPU) in month 
  - Roaming usage

## Recommendations
1. Implement an early warning system based on usage decline
2. Personalize retention offers for high-value customers
3. Improve roaming services and local call plans
4. Develop loyalty programs to encourage consistent recharge behavior

## Future Work
- Incorporate additional data sources (e.g., customer service interactions)
- Develop a real-time churn prediction system
