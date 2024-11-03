## Disability Prediction Analysis Using the American Community Survey (ACS) Dataset
## Project Overview
This project investigates how age, education level, and gender collectively influence the likelihood of experiencing a disability among individuals in the American population. Using data from the 2012 American Community Survey (ACS), we follow a complete data analysis workflow that includes data acquisition, data wrangling, statistical modeling, and result interpretation.

## Table of Contents
Introduction
Data
Computational Methods
Data Analysis
Results and Conclusions
Limitations and Future Work
References

## Introduction
The primary objective is to explore the relationship between demographic variables (age, education level, and gender) and the likelihood of experiencing a disability. A computational approach allows us to manage large datasets and uncover trends that might not be evident through traditional analysis methods.

## Data
Dataset: 2012 American Community Survey (ACS)
The dataset includes demographic, economic, and social characteristics of individuals in the United States. Key fields used in this project include income, employment status, hours worked, race, age, gender, education level, and disability status.

## Computational Methods
Data Wrangling: Data cleaning, renaming columns for clarity, handling missing values, and encoding categorical variables.
Exploratory Analysis: Age distribution across gender, education level, and disability status.
Modeling: Logistic regression to predict disability status using age, education level, and gender as predictors. Model evaluation includes confusion matrix analysis, recall, and cross-validation.

## Data Analysis
The analysis process involves:

Loading and preparing the data.
Visualizing age distribution by disability status.
Running a logistic regression model to determine how age, education level, and gender predict disability.

## Results and Conclusions
The model indicates a significant association between age and the likelihood of experiencing a disability. However, gender and education level were not statistically significant predictors. Model accuracy was validated through cross-validation with an accuracy of 92.02%.

## Limitations and Future Work
The dataset lacks detailed health and lifestyle information, which could enhance predictive power. Future improvements may include integrating health behavior data and exploring interactions between variables.

