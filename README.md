# Employee Data Cleaning with Pandas

## 📌 Project Overview

This project focuses on cleaning and preprocessing a **large, messy employee dataset** using **Python, Pandas, and NumPy**.

The dataset contains missing values, duplicate records, inconsistent text values, invalid numerical values, mixed date formats, and other data-quality issues.

The goal is to transform the raw dataset into a **clean, consistent, and analysis-ready dataset**.

## 🔄 Data Cleaning Process

### 1. Data Loading & Exploration

* Imported Pandas and NumPy
* Loaded the raw CSV dataset
* Checked dataset shape, columns, and data types
* Inspected the overall structure of the dataset

### 2. Duplicate Detection & Removal

* Identified duplicate records
* Removed duplicate rows
* Verified that duplicate records were successfully removed

### 3. Missing Value Analysis

* Checked missing values for each column
* Identified columns requiring imputation
* Identified fields where missing values should be preserved

### 4. Data Type Conversion

* Converted numerical columns from text to numeric format
* Converted `Join_Date` into datetime format
* Used appropriate error handling for invalid values

### 5. Text & Categorical Data Cleaning

* Removed unwanted spaces
* Standardized inconsistent categorical values
* Cleaned columns such as `Department`, `City`, `Employment_Status`, and `Education`
* Converted email values to a consistent format

### 6. Numerical Data Cleaning

* Identified invalid values and outliers
* Cleaned columns such as:

  * `Age`
  * `Monthly_Salary`
  * `Years_At_Company`
  * `Performance_Score`
* Used appropriate numerical data types

### 7. Missing Value Imputation

* Used **mode** for selected categorical columns
* Used **mean or median** for numerical columns based on skewness
* Preserved missing values in fields such as `Employee_ID`, `Email`, and `Join_Date` where artificial values could be misleading

### 8. Data Validation

Performed final checks for:

* Missing values
* Duplicate rows
* Duplicate Employee IDs
* Data types
* Numerical ranges
* Categorical consistency

### 9. Exporting Cleaned Data

The final cleaned dataset was exported as:

```text
cleaned_employee_dataset.csv
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook / VS Code


## 📊 Dataset

The dataset contains **1,000 records and 12 employee-related columns** after duplicate removal.

Key columns include:

`Employee_ID`, `Name`, `Age`, `Department`, `City`, `Monthly_Salary`, `Years_At_Company`, `Join_Date`, `Email`, `Employment_Status`, `Education`, and `Performance_Score`.

## 🎯 Key Learning Outcomes

This project provided hands-on practice with **data preprocessing, missing-value handling, duplicate removal, data-type conversion, categorical cleaning, numerical cleaning, date handling, validation, and preparing real-world messy data for analysis or machine learning.**
