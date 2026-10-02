# ITAI-1371 Midterm Project – Patient Health Records Data Preprocessing

## Group 1
- Viktoriya Kurmisheva
- Tien Manh Nguyen
- Zaid Alayedy

## Project Overview
For this midterm project, our group worked with the Patient Health Records dataset from Kaggle. The goal was to clean and preprocess the raw data so it can later be used for machine learning classification.

The original dataset contains 10,000 records and 17 columns with numerical, categorical, health, lifestyle, medication, and visit information. The target variable is `Has_Disease`, which can be used for a binary classification problem.

## Main Preprocessing Steps
All preprocessing was completed with Python in Jupyter Notebook. The original dataset was not edited manually.

The project includes:

- 70% training and 30% testing split
- EDA performed only on the training data
- Missing-value handling
- Numerical data cleaning
- Age and Blood Pressure corrections
- Categorical data standardization
- One-Hot Encoding
- City frequency encoding
- Class balancing with random oversampling
- Feature engineering
- Log normalization for selected skewed features
- Min-Max Scaling
- Matplotlib before-and-after visualizations
- Printed sample data throughout preprocessing
- Final verification of missing, non-numerical, and infinite values

## Feature Engineering
The following new features were created:

- `Pulse_Pressure`
- `Mean_Arterial_Pressure`
- `Cholesterol_Age_Ratio`

## Final Dataset
After preprocessing, the final training dataset contains:

- 3,518 records
- 31 columns
- No missing feature values
- No non-numerical predictors
- No infinite values
- Balanced `Has_Disease` classes with 1,759 records in each class

The cleaned dataset is ready for future machine learning model training.

## Repository Contents
This repository includes:

- Original dataset document
- Patient Health Records Dataset Proposal
- What We Will Accomplish document
- Main preprocessing Jupyter Notebook
- Before and After Data Processing Jupyter Notebook
- Midterm Reflection
- Team Member Contribution Journal
- Final cleaned training dataset

## Team Contributions
**Viktoriya Kurmisheva** worked on identifier removal, Age and Blood Pressure corrections, categorical cleaning, One-Hot Encoding, and class balancing.

**Tien Manh Nguyen** worked on the 70/30 train-test split, EDA, numerical preparation, date features, and City frequency encoding.

**Zaid Alayedy** worked on feature engineering, normalization, scaling, and final numerical checks.

## Machine Learning Goal
The processed dataset will be used later to train and compare machine learning models that predict the `Has_Disease` target.
