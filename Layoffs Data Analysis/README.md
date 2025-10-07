## Projects Overview

### 1. Data Cleaning with SQL

**Objective:**  
Clean and preprocess raw layoff data for accurate analysis.

**Key Steps:**  
- Removed duplicate rows to ensure data integrity.  
- Standardized key fields such as company, industry, and country for consistency.  
- Addressed and handled null or blank values.  
- Transformed date columns from text to date format for better querying and time-based analysis.  
- Created clean staging tables to avoid changing raw data directly.  
- Updated missing values by referencing other fields, and filtered out irrelevant or incomplete records.

**Skills Used:**  
`ROW_NUMBER()`, `TRIM`, `UPDATE`, `ALTER TABLE`, joining tables, handling nulls, basic ETL using SQL.

### 2. Exploratory Data Analysis with SQL

**Objective:**  
Analyze layoff data to discover trends, key metrics, and business insights.

**Key Steps:**  
- Explored data by calculating maximum, minimum values, and percentage-based statistics.  
- Segmented layoffs by company, industry, country, and year to uncover patterns.  
- Examined trends across business stages, and evaluated rolling monthly totals.  
- Used window functions to understand layoffs dynamics over time and across companies.  
- Applied ranking and aggregation techniques to highlight the top impacted companies per year.

**Skills Used:**  
Aggregation, `GROUP BY`, window functions, trend analysis, ranking (using `DENSE_RANK`), time-series breakdowns.
