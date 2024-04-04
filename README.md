# NashvilleHousing-SQL-Data-Cleaning

## Overview

This project focuses on cleaning and preprocessing Nashville housing data sourced from Kaggle using SQL queries. The dataset contains information on property sales, prices, locations, and property characteristics. The objective is to clean the dataset to ensure accuracy and consistency for further analysis.

## Tasks

### 1. Standardize Date Format
   - Identify date columns in the dataset.
   - Use SQL queries to standardize the date format to ensure consistency across records.

### 2. Populate Property Address Data
   - Identify records with missing property address data.
   - Use available information (e.g., parcel number, location details) to populate missing property addresses where possible.

### 3. Break Out Address into Individual Columns
   - Split the address field into separate columns for address, city, and state.
   - Use SQL queries to extract and separate address components for improved analysis and visualization.

### 4. Change "Y" and "N" to "Yes" and "No" in "Sold as Vacant" Field
   - Identify records where the "Sold as Vacant" field contains "Y" or "N".
   - Use SQL queries to replace "Y" with "Yes" and "N" with "No" for clarity and consistency.

### 5. Remove Duplicates
   - Identify duplicate records in the dataset based on unique identifiers.
   - Use SQL queries to remove duplicate records while preserving essential data.

### 6. Delete Unused Columns
   - Identify columns in the dataset that are not required for analysis.
   - Use SQL queries to delete unused columns to streamline the dataset and improve efficiency.

## Usage

1. **Setup Database**: Ensure the Nashville housing dataset sourced from Kaggle is imported into your SQL database.
2. **Execute SQL Queries**: Run SQL queries provided for each cleaning task to clean and preprocess the data.
3. **Verify Results**: Review the cleaned dataset to ensure data quality and consistency.

## Contributing

Contributions to improve data cleaning processes or address specific issues in the dataset are welcome! Please fork the repository, make your changes, and submit a pull request.

## Data Source

The Nashville housing dataset is sourced from Kaggle. [NashvilleHousing Data Set](link_to_the_dataset).


