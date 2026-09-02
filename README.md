# Decodelabs-Internship-Project-1-Data-Cleaning-And-Preparation

### Data Analytics Project

A practical data cleaning and validation project focused on preparing an e-commerce dataset for reliable downstream analysis.

## Project Overview

The project involved reviewing a raw dataset, identifying data quality issues, applying appropriate cleaning techniques, and validating the resulting dataset.

The main focus was on missing-value handling, data-format standardization, duplicate checks, and maintaining data integrity throughout the cleaning process.

## Objectives

* Identify data quality issues
* Handle missing values appropriately
* Standardize data formats
* Verify unique identifiers
* Check for duplicate records
* Maintain data consistency
* Document the cleaning process
* Prepare the dataset for further analysis

## Tools & Techniques

* Microsoft Excel
* Data Cleaning
* Data Validation
* Data Quality Assurance
* Data Standardization

## Dataset Overview

The dataset contains **1,200 records and 14 columns** covering e-commerce order information.

Key fields include:

* Order ID
* Date
* Customer ID
* Product
* Quantity
* Unit Price
* Shipping Address
* Payment Method
* Order Status
* Tracking Number
* Items in Cart
* Coupon Code
* Referral Source
* Total Price

## Data Cleaning Process

### 1. Missing Value Handling

The `CouponCode` column contained **309 missing values**. These values were replaced with `No Coupon` to preserve the records while clearly representing the absence of a coupon.

### 2. Date Standardization

The `Date` column was standardized to the `yyyy-mm-dd` date format to ensure consistency and improve usability for future analysis.

### 3. Numerical Formatting

The `UnitPrice` and `TotalPrice` columns were standardized to numeric formats with **two decimal places** to maintain consistent precision.

### 4. Duplicate Validation

The `OrderID` column was checked for duplicate values, and no duplicate Order IDs were identified.

Complete records were also checked for duplicates, with no duplicate records identified.

## Validation Results

| Validation Check           | Result          |
| -------------------------- | --------------- |
| Total Records              | 1,200           |
| Total Columns              | 14              |
| Missing Coupon Codes       | 309 → Addressed |
| Duplicate Order IDs        | 0               |
| Duplicate Complete Records | 0               |
| Date Format                | Standardized    |
| Price Formatting           | Standardized    |

## Workbook Structure

The Excel workbook contains three worksheets:

* **RAW DATA** — Original dataset before cleaning
<img width="1919" height="1007" alt="Raw Data" src="https://github.com/user-attachments/assets/83ad900a-7448-40ee-9cd9-f6219d8b923b" />


* **CLEANED DATA** — Processed and standardized dataset
<img width="1919" height="1004" alt="Cleaned Data" src="https://github.com/user-attachments/assets/d8453afa-cc49-453d-b95e-e7f11cec5868" />


* **CHANGE LOG** — Documentation of cleaning and validation activities
<img width="1531" height="323" alt="Change Log" src="https://github.com/user-attachments/assets/961a553a-f4a4-4be0-962d-6eb411c438fe" />


```

## Key Outcome

The raw dataset was cleaned, standardized, and validated while preserving the original records. The resulting dataset provides a structured foundation for further data analysis and visualization.

## Key Learning

This project provided practical experience in handling missing data, standardizing datasets, validating data integrity, and documenting data-cleaning activities before conducting analysis.

## Author

**SHAZMA BATOOL**

**ASPIRING DATA ANALYST | DATA ANALYTICS | EXCEL**
