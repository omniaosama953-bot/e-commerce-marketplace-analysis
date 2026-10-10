# E-Commerce Marketplace Analysis

**Sales Analysis using Python and Power BI**

## Project Overview

In this project, I worked with an e-commerce dataset to analyze sales, profit, product performance, and customer behavior.

I used Python and Pandas to explore and clean the data, then imported the cleaned dataset into Power BI to create a report with different views of sales and customer activity.

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Power BI
- Power Query
- DAX

## Dataset

The dataset contains 9,994 rows and 21 columns. It includes order details, customer information, product categories, sales, quantity, discounts, profit, and shipping mode.

## Data Cleaning

I used Python and Pandas to check the dataset before starting the analysis.

The main steps were:

- Checking for missing values and duplicate rows.
- Finding 11 missing values in the Postal Code column.
- Replacing missing Postal Code values with `0`.
- Checking column data types and preparing the data for analysis.
- Saving the cleaned dataset for use in Power BI.

I kept negative profit values because they can represent orders that resulted in a loss.

## Power BI Analysis

After cleaning the data, I built a Power BI report to explore different parts of the business.

The report includes:

- **Sales and Profit:** Overall performance and monthly trends.
- **Product Performance:** Top 10 products by sales, with comparisons across categories and sub-categories.
- **Regional Sales:** Sales comparison across regions.
- **Customer Analysis:** New, repeat, active, and inactive customers.
- **Customer Retention:** Cohort analysis to track customer activity over time.
- **Shipping Modes:** Order distribution by shipping mode.

I also created a Calendar table and used DAX to calculate Total Sales, Total Profit, Total Orders, and Total Customers.

## What I Learned

This project gave me more practice with data cleaning, working with dates, creating relationships in Power BI, and writing DAX measures.

It also helped me understand how to organize different analyses in one report and use charts to make sales and customer data easier to explore.

## Project Files

- `Raw_data.csv` — Original dataset.
- `Sales_Cleaned.csv` — Cleaned dataset.
- `data_cleaning.ipynb` — Python notebook for data cleaning.
- `E-Commerce_Marketplace_Analysis.pbix` — Power BI report.
