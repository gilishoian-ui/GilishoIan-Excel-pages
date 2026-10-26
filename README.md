 # Retail Sales Transactions Analysis (2022 - 2026)

## Project Overview
This repository documents an end-to-end data analysis project focusing on a retail sales transactions dataset sourced from Kaggle. The goal of this project is to analyze profitability, clean structural anomalies, and evaluate sales performance across different demographic groups.

This is the first project in my data analysis portfolio journey, which will expand to feature dedicated repositories for SQL, Python, Power BI, and multi-tool integrated projects.

## Data Cleaning & Transformation Workflow
To prepare the dataset for analysis, I performed the following data transformations using WPS Office / Excel:

-De-duplication: Identified and removed duplicate records to ensure data integrity.
-Geographical Standardization: Standardized the city column (`city_proper`) to ensure uniform naming conventions across all records.
-Demographic Segmentation:** Engineered a custom `customer_Agegroup` conditional feature to categorize demographics and easily track age-based purchasing behaviors.
-Profitability Logic: Constructed a calculated profit flag column using a dynamic `IF` statement:
-Profit: If value is greater than 0 (`> 0`)
-Loss: If value is less than or equal to 0 (`<= 0`)

## Analytical Approach & Dashboarding
-Pivot Tables:Built several multi-dimensional pivot tables to compare total sales volume and profitability across diverse consumer demographics.
-Dynamic Excel Dashboard: Created a centralized performance dashboard utilizing interactive slicers, allowing stakeholders to filter and explore the sales metrics dynamically.

