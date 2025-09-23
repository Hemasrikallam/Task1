# Task1
Task 1: Data Cleaning &amp; Preprocessing Objective: Learn how to clean and prepare raw data for ML. Tools: Python, Pandas, NumPy, Matplotlib/Seaborn
Titanic Survival Prediction
This notebook performs data analysis, preprocessing, and prepares data for building a machine learning model to predict survival on the Titanic.

Steps:
Data Loading and Initial Inspection: Load the dataset and display basic information and the first few rows.
Handle Missing Values: Impute missing values in 'Age', 'Cabin', and 'Embarked' columns.
Feature Engineering and Encoding: Transform categorical features and create new features where necessary.
Outlier Detection and Removal: Visualize and remove outliers from numerical features using the IQR method.
Feature Scaling: Standardize numerical features.
Dataset
The dataset used is the classic Titanic dataset, containing information about passengers, including whether they survived.

Dependencies
pandas
numpy
matplotlib
seaborn
sklearn
Usage
Run the cells sequentially to perform the data preprocessing steps. The output of the last cell shows the shape of the dataframe after outlier removal and the first few rows of the processed data.
