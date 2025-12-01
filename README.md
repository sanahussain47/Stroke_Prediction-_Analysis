# Stroke_Prediction-_Analysis

Stroke Prediction Analysis – Tools Project
1. Introduction

This project focuses on exploring, analyzing, and modeling a healthcare dataset related to stroke prediction. The dataset contains demographic and clinical attributes such as age, hypertension, heart disease, BMI, glucose level, and lifestyle factors. The primary goal is to perform data loading, preprocessing, exploratory data analysis (EDA), machine learning modeling, and version control using Git.

2. Dataset Description

The dataset consists of the following columns:

id: Unique identifier

gender: Male, Female, Other

age: Age in years

hypertension: 0 = No, 1 = Yes

heart_disease: 0 = No, 1 = Yes

ever_married: Yes/No

work_type: Type of employment

Residence_type: Urban/Rural

avg_glucose_level: Average glucose level

bmi: Body Mass Index

smoking_status: Smoking categories

stroke: Target variable (0 = No, 1 = Yes)

The dataset was sourced from Kaggle.

3. Project Structure
├── data/
│   └── stroke_data.csv
├── notebooks/
│   └── analysis.ipynb


4. Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Git and GitHub for version control

Kaggle for dataset source

5. Steps Completed
5.1 Data Loading

The dataset was loaded using Pandas. Initial inspection was performed using .head(), .info(), and .describe() to understand variable types and missing values.

5.2 Data Wrangling & Cleansing

Handling missing values in bmi column using mean imputation

Encoding categorical variables (Label Encoding and One-Hot Encoding)

Converting binary variables to numeric

Checking for duplicates and removing them

Fixing inconsistent data types where needed

5.3 Exploratory Data Analysis (EDA)

Several visualizations were created:

Distribution plots for numerical variables

Count plots for categorical variables

Comparison of stroke vs non-stroke groups

Correlation heatmap

Boxplots to detect outliers

Observations were recorded for each chart, highlighting trends such as higher stroke prevalence in older individuals and those with hypertension.
