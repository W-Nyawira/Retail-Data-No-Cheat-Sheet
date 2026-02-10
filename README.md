#Project Overview

This project solves the challenge of dealing with large scale data since it contains over 500k retail transactions.While Excel is an excellent tool for 
data visualisation, it struggles with raw and unoptimized datasets. I bridged this gap by using Python for programmatic data cleaning and engineering and 
Excel for high-level executive reporting. 

#Technical workflow

**Programmatic data cleaning and engineering**
Using Jupyter Notebooks I performed the heavy lifting that ensures data integrity. 

1. Merging- I merged different tables using pandas to get a comprehensive dataset.
2. Feature Engineering- I derived time-based features (Year, Month, day, and hour) to capture seasonality.
3. Optimization- I cleaned null values, dropped certain rows, and optimized data types to ensure that the end dataset
   could be visualised in excel.

**Business Intelligence Layer**
The engineered data was imported to excel to build a decision support tool.
1. Interactive slicers to allow stakeholders to filter revenue by month and year.
2. KPI tracking: visualized total revenue, total number of customers, and customers by country.
3. Dynamic charting- Used pivot charts to show the sales trend over time.

#Key Findings
1. The company should capitalize on the fourth quarter of the year since sales peak from September to December.
2. A small number of countries contribute the most revenue with the the UK in the lead.

# Dashboard Preview
<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/3e12a101-bab7-49b1-beb1-6783a73e4ba3" />







