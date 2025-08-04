# MACHINE-LEARNING-PROJECT
Task 1:
Data Cleaning & Preprocessing - Titanic Dataset
This project is part of the AI & ML Internship and focuses on cleaning and preprocessing real-world data for Machine Learning.
OBJECTIVE:
To clean and prepare the Titanic dataset by handling missing values, encoding categorical features, scaling numeric features, and identifying/removing outliers.

Dataset:
Dataset used: Titanic-Dataset.csv
Source: Kaggle Titanic Dataset

Tools & Libraries:
Python 3,Pandas,NumPy,Matplotlib,Seaborn and scikit-learn

Steps Performed:
1. Data Loading & Exploration
Imported the dataset using pandas
Displayed shape, data types, missing values, and summary statistics
2. Missing Value Handling
3. Filled Age with median
Filled Cabin with 'Unknown'
Filled Embarked with mode
3. Encoding Categorical Features
Used Label Encoding for Sex
Used One-Hot Encoding for Embarked
Dropped irrelevant columns: Name, Ticket, Cabin, PassengerId
4. Feature Scaling
Used StandardScaler to normalize Age, Fare, SibSp, Parch
5. Outlier Detection
Used boxplots to visualize outliers
Removed outliers using IQR method
6. Final Dataset
Cleaned data saved as Cleaned_Titan
ic_Dataset.csv

Learnings:
Importance of handling missing data
Difference between one-hot vs label encoding
When to use normalization vs standardization
Identifying and removing outliers
Why preprocessing is crucial for ML model accuracy




