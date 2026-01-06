# Gradient-Boosting
Project Overview

This project demonstrates a complete and professional implementation of Gradient Boosting Regression using Python and scikit-learn.
The objective is to build a high-accuracy regression model by sequentially improving predictions using residual learning.

**Repository Structure**

<img width="948" height="170" alt="image" src="https://github.com/user-attachments/assets/4f3f52a2-c765-431e-9686-37e469979a5e" />


**Dataset Description**

*File:* multiple_linear_regression_dataset.csv

*Type:* Tabular numerical dataset

*Target Variable:* Last column(income)

*Features:* All remaining columns

*Task:* Supervised Regression

The dataset is used to predict a continuous output variable based on multiple input features.

**Algorithm Used: Gradient Boosting Regression**

Gradient Boosting Regression is an ensemble learning method that builds a strong regression model by sequentially adding weak learners (decision trees).

**Residuals Calculation**

<img width="878" height="485" alt="image" src="https://github.com/user-attachments/assets/0bd34f6b-8737-4ed3-8891-79bac0d95493" />

**Prediction**

<img width="1058" height="713" alt="image" src="https://github.com/user-attachments/assets/976848b2-b8fd-4795-a55b-39bfe53f9e5f" />



**Key Characteristics**

1.Uses gradient descent to minimize loss

2.Each tree learns from residual errors

3.Produces high accuracy on non-linear data

4.Widely used in real-world ML systems

**Step-by-Step Methodology**

*Step 1:* Import Required Libraries

1.pandas, numpy

2.scikit-learn modules for modeling and evaluation

*Step 2:* Load Dataset

1.Dataset loaded directly from repository

*Step 3:* Data Inspection

1.Shape, data types, and missing value checks

*Step 4:* Feature–Target Separation

1.Features → Independent variables

2.Target → Dependent variable

*Step 5:* Train–Test Split

1. 80% training data

2. 20% testing data

Step 6: Model Initialization,Model Training 

Gradient Boosting Regressor is configured with:

1.Number of estimators

2.Learning rate

3.Tree depth

4.Subsampling for regularization

*Model Training*

1.Model learns residuals iteratively

2.Trees are added sequentially

*Prediction* 

Predictions generated on test data

*Step 7:* Evaluate Model Performance

1. Performance measured using:

2. Mean Squared Error (MSE)

3. Mean Absolute Error (MAE)

4. R² Score

*Step 8:* Feature Importance Extraction

1. Importance scores extracted

2. Helps interpret model behavior

**Histogram**

<img width="676" height="421" alt="image" src="https://github.com/user-attachments/assets/da59f839-d6c0-4fa7-9db3-2872e852225c" />


*Step 9:* Save the Model

Store the model
