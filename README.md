# Data Cleaning in SQL Queries

## Overview

This repository provides SQL queries for cleaning and standardizing data in the "NashvilleHousing" table within the "PortfolioProject.dbo" schema. The queries address various data cleaning tasks, including standardizing date formats, populating missing property addresses, breaking down addresses into individual columns, transforming "Sold as Vacant" values, removing duplicates, and deleting unused columns.

## How to Use

1. Execute the SQL scripts using your preferred SQL client.
2. Ensure that the necessary database and tables ("PortfolioProject.dbo.NashvilleHousing") are available.

## Contents

1. **Standardize Date Format**
   - Convert and update the SaleDate column.

2. **Populate Property Address Data**
   - Fill missing PropertyAddress values based on matching ParcelID.

3. **Breaking out Address into Individual Columns**
   - Create separate columns for StreetAddress and City based on the PropertyAddress.

4. **Parsing Owner Address**
   - Extract state, city, and address components from the OwnerAddress.

5. **Change Y and N to Yes and No in "Sold as Vacant" Field**
   - Update the SoldAsVacant field to use "Yes" and "No" instead of "Y" and "N".

6. **Remove Duplicates**
   - Identify and display duplicate records based on specific columns.

7. **Delete Unused Columns**
   - Remove columns such as OwnerAddress, TaxDistrict, PropertyAddress, and SaleDate.
