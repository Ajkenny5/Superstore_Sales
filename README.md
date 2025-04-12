# Super Store Sales 

### Project Overview

This report provides an analysis of the dashboard created for sales and business performance evaluation. The dashboard offers key insights into Performance overview of superstore, Segments behavior, Discount impact performance, Sub-categories & Ship-mode performance and regional sales. By using interactive visualizations, the dashboard helps stakeholders make data-driven decisions. This report outlines the objectives, methodology, findings, and recommendations derived from the dashboard analysis.

### Data Source
- The Sample Superstore dataset was collected from kaggle. [Download_Here](https://tinyurl.com/359rzp3c)

### Tools
- Microsoft Excel for Data Cleaning
- Microsoft PowerBi for Data Visualization


### Data Cleaning & Preparation

The Sample Superstore dataset was collected from kaggle. Data preprocessing was done using Microsoft Excel by adding a random date column since the dataset lacked a date column, using the function (“=randbetween(date(2021,1,1), date(2023,12,31)”) and using Power Query to clean and structure the data into eight (8) tables. DAX measures were implemented in Power BI to calculate key performance indicators, including revenue, profit margin, discount amount, and loss percentage.


### Data Modeling

After ensuring my data’s accuracy and consistency, I began the process of creating a data model for my tables. I first establish my data table which is “sales table” then started creating relationships between tables. For this project, I used “one to many” relationship. Screenshot of the completed model is attached below.
