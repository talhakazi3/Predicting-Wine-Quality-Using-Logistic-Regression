# Predicting-Wine-Quality-Using-Logistic-Regression
This project applies Logistic Regression to predict wine quality based on various physicochemical features such as acidity, alcohol content, and sulphates. The goal is to build a robust machine learning model that classifies wines as good or bad based on measurable chemical properties.
🍷 Predicting Wine Quality Using Logistic Regression
📘 Overview

This project applies Logistic Regression to predict wine quality based on various physicochemical features such as acidity, alcohol content, and sulphates.
The goal is to build a robust machine learning model that classifies wines as good or bad based on measurable chemical properties.

🎯 Objectives

Analyze the Wine Quality dataset to understand feature relationships.

Preprocess data for model readiness (handle null values, scaling, encoding).

Train and evaluate a Logistic Regression model for binary classification.

Interpret model performance and identify the most influential features.

📂 Dataset

The dataset used is the Wine Quality Dataset, typically sourced from the UCI Machine Learning Repository
.
It contains several physicochemical attributes of red or white wine samples, including:

🧠 Methodology
1. Data Preprocessing

Checked for missing values and outliers.

Converted wine quality scores into binary categories:

Good (1) → quality > 5

Bad (0) → quality ≤ 5

Normalized feature values for consistent scaling.

2. Exploratory Data Analysis (EDA)

Visualized distributions and correlations using Seaborn and Matplotlib.

Identified key correlations between features and wine quality.

3. Model Development

Split dataset into training (80%) and testing (20%) sets.

Trained a Logistic Regression classifier using Scikit-learn.

Tuned hyperparameters for better accuracy.

4. Model Evaluation

Evaluated performance using the following metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📊 Results

Achieved ~80–85% accuracy on the test dataset.

Alcohol content, volatile acidity, and sulphates emerged as the top predictors of wine quality.

The model provides a simple yet effective baseline for wine quality classification.
