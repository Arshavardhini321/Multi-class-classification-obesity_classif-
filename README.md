# Multi-class-classification-obesity_classif-

# Multi-Class Logistic Regression - Obesity Level Prediction

## Overview

This repository contains my third milestone in my Artificial Intelligence and Machine Learning learning journey.

In this implementation, I explored how **Multi-Class Logistic Regression** can be used to predict an individual's obesity level based on lifestyle, dietary habits, and physical characteristics.

Unlike binary classification problems, this project focuses on **multi-class classification**, where the model predicts one among several obesity categories using **One-vs-All (OvA)** and **One-vs-One (OvO)** strategies.

---

## Problem Statement

Predict an individual's **obesity level** using health and lifestyle-related attributes through Multi-Class Logistic Regression.

This type of predictive model can assist healthcare professionals, nutritionists, and fitness applications in identifying obesity risk levels and supporting preventive healthcare recommendations.

---

## Dataset Features

The dataset includes the following features:

- Gender
- Age
- Height
- Weight
- Family History with Overweight
- Frequent Consumption of High-Calorie Food
- Frequency of Vegetable Consumption
- Number of Main Meals
- Food Consumption Between Meals
- Smoking Habit
- Daily Water Intake
- Calorie Monitoring
- Physical Activity Frequency
- Screen Time
- Alcohol Consumption
- Transportation Method

### Target Variable

**Obesity Level**

The model predicts one of the following obesity categories:

- Insufficient Weight
- Normal Weight
- Overweight Level I
- Overweight Level II
- Obesity Type I
- Obesity Type II
- Obesity Type III

---

## Machine Learning Workflow

- Imported required libraries
- Loaded the dataset
- Performed Exploratory Data Analysis (EDA)
- Checked for missing values
- Applied One-Hot Encoding for categorical variables
- Standardized numerical features
- Split the dataset into training and testing sets
- Implemented Multi-Class Logistic Regression
- Applied One-vs-All (OvA) classification
- Applied One-vs-One (OvO) classification
- Evaluated model performance using Accuracy Score

---

## Visualizations

The notebook includes several visualizations for understanding the dataset, including:

- Feature Distribution
- Correlation Analysis
- Exploratory Data Analysis (EDA)
- Model Performance Comparison

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Files Included

- `Multi_Class_Logistic_Regression.ipynb`
- `Obesity-level-prediction-dataset.csv`
- `README.md`

---

## Key Learning Outcomes

Through this implementation, I learned:

- Difference between Binary and Multi-Class Classification
- One-Hot Encoding for categorical variables
- Feature Scaling using StandardScaler
- Multi-Class Logistic Regression
- One-vs-All (OvA) Classification Strategy
- One-vs-One (OvO) Classification Strategy
- Model Evaluation using Accuracy Score
- End-to-End Machine Learning Workflow

---

## Real-World Applications

Multi-Class Logistic Regression can be applied in several domains, including:

- Healthcare risk assessment
- Disease diagnosis
- Fitness and nutrition recommendation systems
- Medical decision support systems
- Customer segmentation
- Product categorization

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Model comparison with Decision Trees, Random Forests, and Support Vector Machines
- Deployment as a web application

---

## Author

**Arsha Vardhini**

This repository represents the **third milestone** in my AI & Machine Learning learning journey. I am building a portfolio by implementing machine learning algorithms one at a time, understanding their underlying concepts, and exploring their real-world applications.
