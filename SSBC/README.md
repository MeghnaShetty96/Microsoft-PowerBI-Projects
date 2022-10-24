#SSBC

Create a Data Model for Seven Sages Brewing Company

Project 1 of Data Analysis and Visualization with Microsoft Power BI Udacity Nanodegree Program in Introduction to Preparing and Modeling Data course. 

Get Data

Used files are CFO Metrics Tracker.xlsx, Customer List (as of FY2021).txt, SSBC Product Offerings.pdf, USD-CAD Exchange Rates.csv, and Monthly Sales Logs/ downloaded from Udacity.

Project Description

The objective is to clean the datasets and create an efficient data model for a small brewing company that will help them better understand what products are popular and profitable so they can mark smart decisions about what products to prioritize as the company continues to grow. The project demonstrates an understanding of core data modeling principles, including the ability to clean, organize and structure data in Power Query, make a date table, build a data model with the appropriate relationships and filters, and create a simple report using common visualizations and DAX measures.

ETL with Power Query

Promoted first rows to be headers as needed 
Reviewed data types for each field to ensure that they are identified correctly
Renamed ambiguous queries so they can be easily identified during data modeling
Renamed columns for easier usage of them
Removed null values in all datasets

Creating Date Table

A date table has been created using Power Query that is set to dynamically update based on the fact table’s start and end date.

The date table includes the standard fields:
Continuous calendar dates
Month name, month number, calendar years
fiscal periods, fiscal years, and fiscal quarter

Seven Sages' Fiscal year begins on October 1st and runs until September 30th. A transaction on Sept 20th, 2020 would fall in FY 2020, but a transaction on October 20th would land in FY 2021.

Building Relationships Between Tables
A one-to-many relationship exists between the one fact table (Sales Transaction) and four dimension table pointing toward it as shown in the data model.

Writing DAX Measures

To satisfy the CFO's requirements, we have calculated Sales, Cost of Sales, and Gross Profit Margin in two different currencies. The following measures have been created, are present on the data model, and are clearly labeled:

Sales in USD ($)
Cost of Sales USD ($)
Gross Profit Margin (or GPM) in USD (%)
Sales in CAD ($)
Unit Sales by Product (%)
Share of gross profit by Product type (%)

Reporting

The reporting layer includes two tabs.
The first tab has the following:
Two card visualizations
One matrix
A text box that includes an executive summary of the key findings
On the first tab, the totals are as follows:
Total Sales in USD: $167.57K
Total Sales in CAD: $224.21k
% Gross Profit Margin in USD (Year total): 14.7%
Each value is reflected using the correct format and clearly labeled. Time periods use fiscal rather than calendar quarters.
The second tab has a simple table with two columns showing the percentage of sales and share of the gross profit made up by each beer produced at SSBC. This total amounts to 100%.


