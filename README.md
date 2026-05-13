# Luxury Housing Sales Analysis – Bengaluru

## Project Overview

This project analyzes luxury housing sales data in Bengaluru using Python, SQLite, SQL, and Power BI. The objective is to clean and process large-scale real estate data, store it in a database, and create interactive dashboards to generate business insights.

## Technologies Used
Python
Pandas
NumPy
SQLite
SQL
Power BI
Matplotlib
Seaborn

## Project Workflow
### 1. Data Cleaning & Preprocessing
Removed duplicates
Handled missing values
Cleaned inconsistent formats
Normalized text fields

### 2. Feature Engineering

Created new features such as:
Price_per_Sqft
Booking_Flag
Quarter_Number

### 3. Database Integration
Loaded cleaned data into SQLite database
Performed SQL queries for analysis

### 4. Data Visualization

#### Built Power BI dashboard with:

Booking trends  

Builder performance  

Market analysis  

Booking conversion insights  

Geographical analysis  

# Project Architecture

CSV Dataset  

     ↓
Data Cleaning using Pandas  

     ↓
Feature Engineering  

     ↓
SQLite Database  

     ↓
SQL Querying  

     ↓
Streamlit Dashboard  

     ↓
Business Insights  


## Key Insights
Certain micro-markets generate higher luxury housing revenue.  

Higher amenity scores improve booking conversion rates.  

3BHK configurations have the highest demand.  

Digital sales channels contribute more successful bookings.  


## Files Included
data/                  -> Dataset files  

notebooks/             -> Jupyter Notebook  

sql/                   -> SQL queries  

dashboard/             -> Power BI dashboard  

luxury_housing.db      -> SQLite database  

README.md              -> Project documentation  


## Conclusion

This project demonstrates a complete real-world data analytics pipeline involving data cleaning, SQL database integration, business intelligence reporting, and dashboard visualization for real estate market analysis.
