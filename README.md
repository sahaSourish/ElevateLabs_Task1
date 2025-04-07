# Mall Customers Dataset Cleaning

## Overview

This project involves cleaning and preparing the Mall Customers dataset for further analysis. The dataset contains customer information such as CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100). The goal was to clean the data by handling missing values, duplicates, inconsistent formats, and ensuring proper data types.

### Steps Taken
- Loading the Dataset:

The dataset was loaded using Python's Pandas library.

- Handling Missing Values:

Checked for missing values using .isnull(). No missing values were found.

- Removing Duplicates:

Used .drop_duplicates() to check and remove duplicate rows. No duplicates were present.

- Standardizing Text Values:

The Gender column was standardized to lowercase (male, female) for consistency.

- Renaming Columns:

Column names were cleaned to be lowercase and spaces were replaced with underscores for uniformity:

## -- CustomerID → customerid

## -- Gender → gender

## -- Age → age

## -- Annual Income (k$) → annual_income_(k$)

## -- Spending Score (1-100) → spending_score_(1-100)

- Fixing Data Types:

Ensured columns had appropriate data types:

-- customerid, age, annual_income_(k$), and spending_score_(1-100) were converted to integers.

-- gender remained as a string.

- Saving the Cleaned Dataset:

The cleaned dataset was saved as Mall_Customers_Cleaned.csv.

# Tools Used
-- Python Libraries:

--- Pandas for data manipulation

--- NumPy for numerical operations

# Dataset:

-- Mall Customers dataset (Mall_Customers.csv)
