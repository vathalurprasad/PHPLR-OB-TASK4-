# PHPLR-OB-TASK4-

# House Price Prediction using Linear Regression
This project is part of my Data Analyst Internship, where I worked on analyzing and predicting house prices using a real-world housing dataset. The primary goal was to build a predictive model using Linear Regression and derive insights through data visualization and evaluation.

# Project Objectives
Understand the structure and patterns in housing data

Identify key features that influence house prices

Build and evaluate a machine learning model to predict prices

Visualize insights using charts and actual vs predicted comparisons

# Dataset Overview
The dataset contains 545 entries with various features such as:

Area (in sq. ft)

 Bedrooms,  Bathrooms, Stories

 Parking availability

 Utility features like Air Conditioning, Basement, Hot Water Heating

Furnishing Status and whether the house is on the Main Road

The target variable is Price, which the model aims to predict.

# Data Processing Steps
Data Cleaning

Checked for null values (none found – dataset is clean)

Basic exploration using summary statistics and visualizations

Encoding Categorical Variables

Converted features like "yes/no" and "furnished/semi-furnished/unfurnished" into numerical format

Feature Selection & Preparation

Removed unnecessary or redundant fields

Selected features that had a strong correlation with house prices

# Model Building
Used Linear Regression from sklearn to build the predictive model

Split the dataset into 80% training and 20% testing

Trained the model on the training set and made predictions on the test set

# Evaluation & Results
Mean Squared Error (MSE): 1.77 trillion

R² Score: 64.9% accuracy in predicting house prices

The model provides a good baseline performance, and there's room for improvement using more advanced algorithms (like Random Forest or XGBoost).

# Visual Insights
Created scatter plots to compare actual vs predicted prices

 # Identified key features influencing price:

Area

Furnishing Status

Air Conditioning

Location (Main Road / Preferred Area)

# Key Learnings
Hands-on experience with real-world data preprocessing

Understanding linear regression mechanics

Importance of data encoding and model evaluation

Interpreting results with visualizations
