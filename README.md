# Vehicle Insurance Customer Exploratory Data Analysis

Python-based exploratory data analysis of vehicle-insurance customer and policy data using Pandas and NumPy.

## Project Overview

This project analyzes customer and insurance-policy information for a vehicle-insurance business scenario.

The analysis combines customer details with policy information to create a consolidated dataset that can be explored for customer and premium-related patterns.

## Business Context

The project is based on a scenario in which an insurance company wants to better understand its customers and policy information to support decisions related to premium discounts.

## Project Workflow

The analysis includes:

1. Loading customer and policy datasets.
2. Inspecting the structure and quality of the data.
3. Cleaning and preparing the datasets.
4. Combining customer and policy information.
5. Creating a master dataset for analysis.
6. Exploring customer and insurance-related variables.
7. Investigating premium-related patterns.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Exploratory Data Analysis
- Data Cleaning
- Data Manipulation

## Repository Structure

```text
vehicle-insurance-customer-eda/
├── README.md
├── .gitignore
└── notebooks/
    └── vehicle_insurance_customer_eda.ipynb
```

## Main Analysis

The complete analysis is available in:

`notebooks/vehicle_insurance_customer_eda.ipynb`

The notebook contains the data preparation and exploratory analysis workflow used for the project.

## Portfolio Scope

This project demonstrates practical experience with:

- working with structured business data
- cleaning and preparing datasets
- using Pandas DataFrames
- manipulating data with Python
- combining information from multiple tables
- exploratory data analysis
- translating a business question into a data-analysis workflow

## Analysis Limitations

This project is an exploratory data-analysis exercise, and several preprocessing choices in the original notebook should be considered when interpreting the results:

- Missing numerical values in the policy data are handled using a broad mean-based imputation approach, which may affect the original distributions.
- Missing age values are handled using mode-based imputation.
- The notebook investigates potential outliers using the interquartile range (IQR) method.
- Some string-cleaning and duplicate-removal operations in the original notebook are evaluated without permanently assigning the transformed result back to the source DataFrame.
- Correlation analysis is exploratory and should not be interpreted as evidence of causation.
- The analysis does not constitute a validated insurance pricing, risk-assessment, or predictive model.

These limitations are documented to keep the portfolio representation transparent and reproducible.

No machine-learning or predictive insurance model is claimed in this repository.
