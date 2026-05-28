# Mall Customers Data Cleaning

## Project Overview
This project involves cleaning the Mall Customers dataset using Python and Pandas.

## Dataset
- **Source:** Kaggle
- **Rows:** 200
- **Columns:** CustomerID, Gender, Age, Annual Income, Spending Score

## What I Did
1. Loaded the dataset and checked for missing values using `.isnull()`
2. Checked and removed duplicate rows using `.drop_duplicates()`
3. Standardized text values in the Gender column to lowercase
4. Renamed column headers to be clean, lowercase, and without spaces
5. Verified all data types were correct

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Files
- `Mall_Customers.csv` — original raw dataset
- `Mall_Customers_Cleaned.csv` — cleaned dataset
- `data_cleaning.ipynb` — Jupyter notebook with full code
