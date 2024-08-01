University Admission Prediction
Project Overview
This project aims to predict the probability of a student being admitted to a university based on their profile using regression models. The input features include GRE Scores, TOEFL Scores, University Rating, Statement of Purpose (SOP), Letter of Recommendation (LOR) Strength, Undergraduate GPA, and Research Experience. The target variable is the chance of admission, represented as a value between 0 and 1.

Data Source: Kaggle - Graduate Admissions Dataset
Photo Credit: Pexels
Dataset Overview
Dataset: Graduate Admissions Dataset
Metrics: 500 rows, 9 columns
Features:
GRE Score (out of 340)
TOEFL Score (out of 120)
IELTS Score (out of 9)
University Rating (out of 5)
Statement of Purpose (SOP) (out of 5)
Letter of Recommendation (LOR) (out of 5)
Undergraduate GPA
Research Experience (0 or 1)
Chance of Admission (0 to 1)
Project Objectives
To explore regression and classification problems, particularly in the context of university admissions.
To extract insights from data using exploratory data analysis (EDA) and visualization techniques.
To implement and compare various machine learning models, including Multiple Linear Regression, Artificial Neural Networks (ANN), Random Forest, and Decision Tree Regressors.
To assess the models' performance using appropriate metrics.
To develop a web application using the Flask framework to present the admission prediction model.
Project Structure
Task 1: Import Libraries and Dataset

Import necessary libraries and load the dataset.
Perform initial data cleaning, including removing irrelevant columns.
Task 2: Perform Exploratory Data Analysis

Check for missing values and data types.
Compute descriptive statistics and group data by university rating.
Task 3: Perform Data Visualization

Visualize data distributions and relationships using histograms, pair plots, scatter plots, and a correlation heatmap.
Task 4: Create Training and Testing Datasets

Split the data into features (X) and target (y).
Scale the data and split it into training and testing sets.
Task 5: Train and Evaluate a Multiple Linear Regression Model

Train a Linear Regression model and evaluate its performance.
Task 6: Train and Evaluate an Artificial Neural Networks Model

Implement an ANN with multiple dense layers, activation functions, and dropout layers.
Train the model and evaluate its performance.
Task 7: Train and Evaluate Random Forest and Decision Tree Regressors

Train and evaluate Decision Tree and Random Forest models.
Task 8: Understand the Difference Between Regression KPIs

Explore key performance indicators (KPIs) such as RMSE, MSE, MAE, R², and Adjusted R².
Task 9: Calculate Regression Model KPIs

Calculate and interpret KPIs for the best-performing model.
This documentation provides a high-level overview of the project. For detailed code implementation and results, please refer to the respective files in the repository.