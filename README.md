# Elevate_Labs_Task1

Mall Customer Data Cleaning

This project walks through the key steps to clean and prepare the `Mall_Customer.csv` dataset using pandas in Python.

## What I Did

1. **Loaded the data** from the CSV file into a pandas DataFrame.
2. **Cleaned the data** by removing any rows that had missing values.
3. **Got rid of duplicate rows** to ensure data quality.
4. **Standardized text fields** like the `gender` column by converting all entries to lowercase and removing extra spaces.
5. **Cleaned up the column headers** by making them lowercase, replacing spaces with underscores, and removing special characters.
6. **Checked and corrected the data types** — making sure numeric columns are stored as integers and text columns like `gender` use pandas’ efficient categorical type.
7. **Displayed how pandas internally stores categorical columns** by showing the unique categories and their corresponding codes.

## What I Used

- Jupyter Notebook
- pandas (Python library)
