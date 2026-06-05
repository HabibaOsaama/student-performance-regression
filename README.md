# Student Performance Prediction (Regression)

## Project Overview
This repository contains a machine learning project originally developed as a Kaggle notebook. The goal of this project is to predict student academic performance (e.g., final exam scores or GPA) using various regression techniques. 

By analyzing demographic, behavioral, and past academic data, this project identifies the key factors that influence a student's success and builds a model to forecast future outcomes.

## Dataset
The data used for this project was sourced from Kaggle: https://www.kaggle.com/datasets/dskagglemt/student-performance-data-set
It includes features such as:
* Study hours per week
* Previous test scores
* Attendance rates
* Demographic background

## Methodology
The notebook walks through the end-to-end data science lifecycle:
1. **Exploratory Data Analysis (EDA):** Visualizing correlations between study habits and final scores.
2. **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
3. **Model Building:** Training and comparing multiple regression models, including:
   * Linear Regression
   * Random Forest Regressor

4. **Evaluation:** Assessing model performance using metrics like Root Mean Squared Error (RMSE) and R-squared ($R^2$).

## Results
The best performing model was the Random Forest Regressor achieving an $R^2$ score of **[0.93]** indicating strong predictive accuracy.

