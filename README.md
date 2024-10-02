# Assignment 01: Learning from Data and Related Challenges & Linear Models for Regression



---

## Overview

This assignment focuses on the foundational aspects of learning from data and the application of linear regression models. It includes tasks on data pre-processing, linear regression modeling, and the evaluation of regression models using real-world datasets.

---

## Contents

### 1. Data Pre-processing

- Analyze the scaling of features using different scaling methods such as:
  - Standard scaling
  - Min-max scaling
  - Max-abs scaling
- Select the most appropriate scaling method to preserve the structure and properties of features.

### 2. Learning from Data

- Generate sample data using Python code to observe how training and testing data differ in each run due to random splits.
- Fit a linear regression model multiple times and analyze why the model varies in each instance.
- Experiment with different sample sizes (100 and 10,000) and compare the model's behavior.

### 3. Linear Regression on Real-World Data

- Utilize a dataset from the UCI repository to perform linear regression.
- Pre-process the dataset by handling missing values.
- Train a linear regression model using selected features and evaluate the model's coefficients.
- Identify the feature contributing most to the dependent variable.
- Calculate performance metrics like:
  - Residual Sum of Squares (RSS)
  - Mean Squared Error (MSE)
  - R-squared (R²)

### 4. Performance Evaluation of Linear Regression

- Compare two models based on their **Residual Standard Error (RSE)** and **R²** to determine which model performs better.
- Discuss which performance metric is more appropriate for comparing models.

### 5. Linear Regression Impact on Outliers

- Investigate the robustness of linear regression in the presence of outliers.
- Explore alternative loss functions to reduce the impact of outliers.
- Analyze the behavior of these loss functions based on hyper-parameter values.

---

## Additional Resources

- [Scikit-learn Preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)
- [Introduction to Sparsity in Signal Processing](https://eeweb.engineering.nyu.edu/iselesni/lecture_notes/sparsity_intro/sparse_SP_intro.pdf)
- [Sklearn Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)



