# Retail-Data-No-Cheat-Sheet
A practical data-cleaning case study focused on uncovering and validating data issues in raw retail transactions in preparation for analysis and modelling. 

#Project Overview
This project focuses on cleaning and validating raw retail data to ensure that it is accurate for revenue and customer analysis. 
The data contains issues that require investigation instead of predefined cleaning rules. 

#Objective
To prepare an analysis ready dataset by identifying, validating, and resolving data inconsistencies that would lead distort business insights. 

#Dataset
Source: Kaggle-Online Retail Dataset.
Type: Transaction-level retail data. 
Size: 540,000 rows(raw)

#Data Quality Issues Identified
The exploratory analysis revealed the following issues:
-Missing customer identifies. 
-Negative quantities associated with cancellations. 
-Zero or negative unit prices. 
-Inconsistent data types and text formatting issues. 

#Cleaning Approach
Cleaning decisions were based on the observed data patterns and retail logic. 
Key steps included:
-Excluding recordings that had missing customer identifiers. 
-Identifying and removing cancellation transactions. 
-Filtering invalid quantities and prices. 
-Normalizing data and text fields. 
-Creating derived fields to support downstream analysis.

All the assumptions were validated using thorough exploratory checks and documentation. 

#Outcomes 
The cleaned dataset contained the following:
-Completed retail transactions. 
-Reliable revenue metrics. 
-Information for time-based analysis. 
-A foundation for EDA and modelling. 

#Repository structure
-Notebook...data cleaning.
-Data

#Next Steps
-Exploratory Data Analysis (EDA)
-Customer Segmentation.
-Revenue and sales trend analysis





