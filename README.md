# Titanic Dataset - Data Cleaning & Preprocessing

## Task

The goal of this task was to clean and prepare the Titanic dataset for machine learning.

## What I Did

- Loaded the dataset using pandas
- Checked for missing values and data types
- Filled missing values in the Age and Embarked columns
- Dropped the Cabin column (too many missing values)
- Converted Sex and Embarked columns into numbers using one-hot encoding
- Standardized the Age and Fare columns
- Removed outliers from the Fare column using boxplot and IQR method
- Saved the cleaned data to a new CSV file


 
## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

   
## Files
- `Titanic-Dataset.csv` – original dataset
- `titanic_cleaned.csv` – cleaned dataset
- `preprocessing.ipynb` – code notebook
