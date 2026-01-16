Data Cleaning & Missing Value Handling
Overview:
This task focuses on cleaning the Medical Appointment No Shows dataset by identifying and handling missing values to improve data quality and prepare the dataset for analysis and machine learning.

Dataset: medical appointment dataset.csv
Tools Used: Python, Pandas, Matplotlib

Steps Performed:
Loaded the dataset and identified missing values using isnull().sum().
Visualized missing data patterns using a bar chart.
Applied mean imputation for numerical columns.
Applied mode imputation for categorical columns.
Removed columns with more than 70% missing values.
Validated the dataset using missing value checks, data types, and info().
Compared dataset size and quality before and after cleaning.

Before vs After Summary:
Columns reduced after removing high-missing features
Missing values minimized
Dataset quality and consistency improved

Final Outcome:
The cleaned dataset contains minimal missing values and is suitable for further analysis and machine learning tasks.

Repository Contents:
Dataset file
Data cleaning notebook
README file