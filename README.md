# Customer Churn Prediction using Logistic Regression (R)
This project implements a Customer Churn Prediction model using Logistic Regression in R to predict whether a customer will churn (leave) based on various features such as age, subscription plan, total spend, and tenure with the service.

# Objective
The goal of this project is to build a machine learning model that can predict whether a customer will churn, helping businesses take proactive steps to retain their customers. Logistic regression, a binary classification algorithm, is used to predict this outcome.

# Dataset
The dataset used in this project contains the following columns:

1.age: Age of the customer.
2.subscription_plan: The plan the customer is subscribed to (e.g., Basic, Premium).
3.total_spend: Total amount spent by the customer.
4.tenure: Number of months the customer has been with the service.
5.churn: Target variable (1 = Churned, 0 = Stayed).

This dataset can be substituted with real-world customer data (e.g., the Telco Customer Churn dataset).

# Technologies Used
1. R: Programming language for data analysis and machine learning.
2. dplyr: For data manipulation and preprocessing.
3. ggplot2: For data visualization (optional).
4. caTools: For splitting the dataset into training and test sets.
5. caret: For building and evaluating the logistic regression model.

# Installation
To run the project locally, clone the repository and install the necessary R packages

Install the required R packages

install.packages(c("dplyr", "caTools", "caret", "ggplot2"))

# Project Workflow

Data Preprocessing: The dataset is cleaned, and categorical features (such as subscription_plan) are encoded using factors.

Model Training: A logistic regression model is trained using the glm function in R.

Model Evaluation: The model is evaluated using accuracy and confusion matrix metrics from the caret package.

