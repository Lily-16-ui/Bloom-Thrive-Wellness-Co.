# BLOOM & THRIVE WELLNESS CO.

### TABLE OF CONTENTS
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis/Key Questions](#exploratory-data-analysis/key-questions)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references) 

### PROJECT OVERVIEW
This project is targeted at revealing deeper and clearer insights into the customer behavior and product performance across all customer based regions of Bloom & Thrive Wellness Co. Through analysis of this data we hope to make meaningful recommendations to aid better product performance.
![Screenshot 2025-06-09 190940](https://github.com/user-attachments/assets/0d82848c-b6a2-4e35-bdec-d6f3c62d01b1)

### DATA SOURCES
- Bloom & Thrive Wellness Co.

### TOOLS
- Excel – Data Cleaning and Visualizations
- SQL – Data Analysis

### DATA CLEANING / PREPARATION 
- Duplicated the dataset to keep the original data set
- Auto fitted the rows and columns
- Removed Duplicates
- Formatted headers 

### EXPLORATORY DATA ANALYSIS (EDA) / KEY QUESTIONS
1.	What are our top-performing products and categories?
2.	How have our monthly sales trended over the past year?
3.	Are there any noticeable patterns in customer purchasing behavior (e.g.; repeated purchases, average order value?) 
4.	Which regions are driving the most sales and are there any underperforming areas?
5.	Are there any sales dips or spikes that we should be concerned about or look into?

### DATA ANALYSIS
---sql

--SELECT *
--FROM [BLOOM & THRIVE WELLNESS CO.].[dbo].['Data Sheet$'] 
--SELECT YEAR([Order Date]) AS OrderYear, DATENAME(MONTH, [Order Date]) AS OrderMonth,

--SUM([Order Value]) AS TotalSales
--FROM [BLOOM & THRIVE WELLNESS CO.].[dbo].['Data Sheet$']
--WHERE [Order Date] BETWEEN '2024-05-01' AND '2025-04-30' 
--GROUP BY YEAR([Order Date]), DATENAME(MONTH, [Order Date]), MONTH([Order Date])
--ORDER BY OrderYear, MONTH([Order Date]); 

### RESULTS / FINDINGS
The results are summarized as follows:
1.	The top-performing products and categories are:
    - Skincare – Suffer, Exactly, Soon, Especially 
    - Fitness Equipment – Present
    - Supplements – Performance, President, Goal, Have, Finish 
2.	Over the past year, there seems to be an equal increase and decrease level in the monthly products sales. 
![Screenshot 2025-06-09 191543](https://github.com/user-attachments/assets/7485247c-6a11-4a6e-ba8a-56945e3f3b81)
3.	There are no observable patterns in the data.
4.	The Eastern region is the underperforming area.
![Screenshot 2025-06-09 191518](https://github.com/user-attachments/assets/17486b25-33a7-476e-8458-b21c43cd3c25)
5.  NO, based on the data provided there hasn’t been any sudden dips or spikes in sales that require attention.

### RECOMMENDATIONS 
- Based on the data analysis, we recommend the following actions:
- More effort should be put into the advertisement of other products asides skincare, given skincare products total sales surpasses that of others.
- There is no record of sales in the Northern region within the last year, I would recommend putting more attention to marketing in that region.
- I would also recommend increasing the marketing of these products in the Eastern region due to its underperformance. 

### LIMITATIONS 
- I had to run visualizations in Excel to determine if there were any noticeable trends or patterns, due to inability to do that in SQL.

### REFERENCES
- Excel 2016
- Microsoft SQL Server Management Studio
- Bloom & Thrive Wellness Co.



