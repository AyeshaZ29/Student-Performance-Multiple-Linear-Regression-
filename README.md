 ******Student Performance Prediction – ML Project******

This project analyzes student performance data and builds predictive models using multiple regression algorithms. The goal is to understand how different factors (study hours, sleep hours, extracurricular activities, etc.) impact the Performance Index.

**Project Overview**

This repository contains:

Data exploration (EDA)

Data cleaning & preprocessing

Feature engineering

Visualizations

Machine learning model training & evaluation

Comparison of multiple regression models

You can use this project as a starter template for supervised regression tasks.

** Dataset**

Source: Kaggle – Student Performance Multiple Linear Regression
Columns include:

Sleep Hours

Study Hours

Sample Question Papers Practiced

Extracurricular Activities

Performance Index (Target)

**Data Cleaning Steps**

✔ Checked missing values and filled them
✔ Removed duplicates
✔ Cleaned categorical values (standardized Yes/No)
✔ Detected invalid data ranges (e.g., Sleep Hours > 24)
✔ Encoded categorical variable

**Exploratory Data Analysis (EDA)**

The notebook includes:

Head, shape, dtypes

Numerical & categorical summaries

Distribution plots

Correlation heatmap

Feature range inspection

Visualizations created using matplotlib and seaborn.

**Feature Engineering**

Label encoding for categorical column

Mapping Extracurricular Activities → {1, 0}

Train–test split (80/20)

Removing duplicates

Handling missing values

 **Machine Learning Models Used**
 
Model	Accuracy (R² Score %)
Linear Regression	~98.84%
Decision Tree Regressor	~97.53%
Support Vector Regression (SVR)	~98.48%
Random Forest Regressor	~98.49%
Gradient Boosting Regressor	~98.82%

Final results show that Linear Regression and Gradient Boosting performed the best.

**Libraries Used**

numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
