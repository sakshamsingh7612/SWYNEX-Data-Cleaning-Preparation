# SWYNEX Internship — Task 1: Data Cleaning & Preparation

## Project Overview

This project demonstrates a data-cleaning and preparation workflow using Python and Pandas. The dataset used is the IBM Telco Customer Churn dataset, which contains customer information, service subscriptions, billing details, and churn status.

## Objectives

* Import and inspect a CSV dataset using Pandas.
* Identify missing values and duplicate records.
* Examine data types and inconsistent categorical values.
* Convert numeric columns to appropriate data types.
* Apply documented data-cleaning rules.
* Validate the cleaned dataset and export the results.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Google Colab
* GitHub

## Dataset Source

IBM Telco Customer Churn dataset:

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

The dataset is used for educational and analytical practice.

## Project Files

* `SWYNEX_Task1_Data_Cleaning.ipynb` — Python notebook containing the inspection, cleaning, and validation steps.
* `Telco-Customer-Churn-Cleaned.csv` — exported cleaned dataset.
* `SWYNEX_Data_Cleaning_Report.csv` — summary of data-quality checks before and after cleaning.

## Data Quality Checks

The notebook checks for:

* Missing and blank values
* Duplicate records and customer IDs
* Incorrect or unexpected data types
* Inconsistent categorical values
* Invalid numeric values and unusual ranges

## Cleaning Approach

Text values are standardized where appropriate, numeric columns are converted to numeric types, and missing total charges are handled using a documented rule for zero-tenure customers. Duplicate records and unexpected values are investigated before corrective action is taken.

## Validation

The cleaned data is checked again for missing values, duplicate records, data types, and potential inconsistencies. The actual findings and results are documented in the notebook.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Inspect the outputs and validation results.
4. Download the cleaned dataset and cleaning report.

## Learning Outcomes

This project provides practical experience with data inspection, data quality assessment, data transformation, validation, and reproducible data-cleaning workflows.

**Note:** Update this README after running the notebook so that all descriptions and reported results match the actual output of your project.

