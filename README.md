Boston Housing Price Prediction using Multiple Linear Regression

 Project Overview

This project focuses on predicting the **median value of houses (MEDV)** in different neighborhoods using **Multiple Linear Regression**. The model uses several housing and neighborhood features to estimate house prices.

The aim of this project is to understand how different factors such as the number of rooms, pollution levels, and population characteristics influence housing prices.

 Dataset

The dataset used for this project is the **Boston Housing Dataset**.

Dataset source:
https://www.kaggle.com/datasets/prateekmaj21/boston-housing-dataset

 Features Used

The following numerical features are used as predictors:

* **RM** – Average number of rooms per dwelling
* **LSTAT** – Percentage of lower status population
* **PTRATIO** – Pupil-teacher ratio by town
* **INDUS** – Proportion of non-retail business acres per town
* **NOX** – Nitric oxides concentration
* **AGE** – Proportion of owner-occupied units built before 1940

 Target Variable

* **MEDV** – Median value of owner-occupied homes

 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

 Steps Performed

1. Loaded the dataset using pandas.
2. Explored the dataset using `head()`, `describe()`, and checked for missing values.
3. Removed rows containing missing values.
4. Selected important features and defined the target variable.
5. Split the dataset into **training (80%)** and **testing (20%)** sets.
6. Built a **Multiple Linear Regression model** using scikit-learn.
7. Predicted housing prices on the test dataset.
8. Evaluated the model using **Mean Squared Error (MSE)** and **R² score**.
9. Visualized the relationship between **actual and predicted house prices** using a scatter plot.

 Results

The model predicts house prices based on the selected features and provides evaluation metrics such as MSE and R² to measure performance.

Visualization

A scatter plot is used to compare **actual house prices** and **predicted house prices**, helping to understand how well the model performs.


