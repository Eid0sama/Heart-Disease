# Heart-Disease
Overview
This repository contains code for analyzing heart disease risk factors and building a predictive model using Python libraries such as Pandas, NumPy, Seaborn, Plotly, and Scikit-learn. The primary objectives are to explore the dataset, identify risk factors, and develop a predictive model for heart disease.

#Contents
#1. Introduction
The dataset used: Heart_2020_cleaned.csv
#2. Description
data_analysis.ipynb: Jupyter Notebook containing the code for exploratory data analysis and model building.
#3. Libraries Used
Pandas
NumPy
Seaborn
Matplotlib
Plotly
Scikit-learn
Datasist
Imbalanced-learn (for SMOTE)
Steps and Analysis
#Exploratory Data Analysis (EDA)
Loaded the dataset using Pandas.
Checked for duplicate records and removed them.
Explored the dataset's structure and summary statistics using datasist.describe().
#Risk Factors Analysis
Analyzed risk factors such as kidney disease, diabetes, stroke, asthma, skin cancer, smoking, alcohol drinking, and physical activity in relation to heart disease.
Visualized count plots and pie charts to show the distribution of heart disease among different risk factors.
#Data Preprocessing
Encoded categorical variables using LabelEncoder.
Handled the imbalance in the target variable ('HeartDisease') using Synthetic Minority Over-sampling Technique (SMOTE).
#Model Training
Split the data into training and testing sets.
Trained the model using Logistic Regression (not shown in the provided code).
#Model Evaluation
Evaluated the model's performance metrics (not shown in the provided code).
Visualized the correlation matrix using a heatmap.
#Conclusion
Key insights from the data analysis.
Future steps: Potential improvements for the model or further analysis.
