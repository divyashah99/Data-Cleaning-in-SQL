# Data Cleaning in SQL: Nashville Housing Dataset

## Problem Statement

This GitHub repository addresses critical data quality issues within the Nashville Housing dataset. The dataset, initially riddled with inconsistencies and gaps, required a comprehensive data cleaning process. The primary objectives were to enhance the overall data quality, standardize formats, and streamline the dataset for more effective analysis.

## Project Overview

The specific problems identified and corresponding solutions implemented are outlined below:

### Standardize Data Format

- **Convert "SaleDate" Column:**
  - **Problem:** Inconsistent date formats in the "SaleDate" column hindered analysis.
  - **Solution:** Applied SQL queries to standardize the "SaleDate" column, ensuring a uniform date format for accurate analysis.

### Populate Property Address Data

- **Identify and Update Missing "PropertyAddress" Values:**
  - **Problem:** Missing "PropertyAddress" values posed challenges in location-based analysis.
  - **Solution:** Leveraged related records to identify and update missing "PropertyAddress" values, enhancing the dataset's completeness.

### Breaking out Address into Individual Columns

- **Split "PropertyAddress" Column:**
  - **Problem:** Lack of structure in the "PropertyAddress" column hindered address-related analyses.
  - **Solution:** Split the "PropertyAddress" column into separate "Address" and "City" columns, improving data organization.

### Change Y and N to Yes and No

- **Update "SoldAsVacant" Column:**
  - **Problem:** Non-descriptive 'Y' and 'N' values in the "SoldAsVacant" column.
  - **Solution:** Replaced 'Y' with 'Yes' and 'N' with 'No' for clarity in vacant property status.

### Remove Duplicates

- **Identify and Display Duplicate Records:**
  - **Problem:** Presence of duplicate records hindered accurate analysis.
  - **Solution:** Implemented criteria to identify and display duplicate records, facilitating the identification and resolution of redundancy.

### Delete Unused Columns

- **Remove Specified Columns:**
  - **Problem:** Unnecessary columns cluttered the dataset.
  - **Solution:** Eliminated specified columns ("OwnerAddress," "TaxDistrict," "PropertyAddress," "SaleDate") to streamline the dataset for focused analysis.

## Impact

This data cleaning initiative has significantly improved the quality and usability of the Nashville Housing dataset. Addressing these issues ensures that analysts and stakeholders can confidently utilize the dataset for accurate and informed decision-making processes.
