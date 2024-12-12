# Diabetes-Prediction-Analysis
This project involves analyzing and visualizing the Diabetes dataset to explore relationships among features and understand the dataset's structure. The dataset contains information related to diabetes prediction.

Features of the Dataset
Pregnancies: Number of pregnancies.
Glucose: Plasma glucose concentration.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skinfold thickness (mm).
Insulin: 2-hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: Diabetes pedigree function (a measure of hereditary risk).
Age: Age of the individual.
Outcome: Target variable (1 = Diabetes, 0 = No Diabetes).
Project Steps
Importing Libraries:

Essential libraries such as pandas, numpy, matplotlib, and seaborn were used for data manipulation and visualization.
Data Loading:

The dataset is loaded using pandas from a .csv file.
Exploratory Data Analysis:

Displaying dataset structure using .head(), .columns, and .dtypes.
Checking for missing values using .isnull().sum().
Data Visualization:

Correlation Matrix: Generated using sns.heatmap to understand relationships between features.
Distribution Plots: Visualized the distribution of features using seaborn plots (adapted to displot or histplot for deprecated distplot).
Descriptive Statistics: Summary of the dataset using .describe().
Data Imputation:

Addressed zero values in features like BloodPressure, SkinThickness, Insulin, and BMI by replacing them with mean or median values as appropriate.
Output
Heatmap: Correlation heatmap to analyze feature relationships.
Feature Distributions: Visualized distributions for features such as Pregnancies, Glucose, Insulin, etc.
Descriptive Statistics: Insights into the central tendency and spread of the data.
Tools and Libraries
Python Libraries: pandas, numpy, matplotlib, seaborn.
Environment: Google Colab.
Notes
This project is focused on data preprocessing and visualization to gain insights into the dataset.
Further steps, such as building a machine learning model for diabetes prediction, can be integrated into this project.
