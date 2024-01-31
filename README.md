# Sales Analysis Project 
## Introduction
This project leverages the capabilities of Python's Pandas and Matplotlib libraries to analyze a comprehensive dataset containing a year's worth of sales data from an electronics store. The dataset includes various transaction details such as month, product type, cost, purchase address, and more.

## Data Cleaning
During this phase, we perform various data cleaning tasks to ensure data integrity and facilitate meaningful analysis:

1. Drop NaN values from DataFrame
Remove missing values to enhance data completeness.
2. Removing Rows Based on a Condition
Filter out rows that don't meet specific criteria to improve data quality.
3. Change the Type of Columns
Transform data types using methods like to_numeric, to_datetime, and astype for better analysis.

Business Questions:
Q1 - Best Month for Sales: Determining the highest-performing sales month and the revenue generated during that period.
Q2 - Most Productive City: Identifying the city that recorded the highest volume of product sales.
Q3 - Optimal Advertisement Timing: Pinpointing the ideal time to display advertisements to increase the likelihood of customer purchases.
Q4 - Frequently Sold Together Products: Analyzing which products are frequently sold together.
Q5 - Top-Selling Product Analysis: Understanding the top-selling product and hypothesizing reasons behind its success.
Methodology
To address these questions, we utilize various methods from Pandas and Matplotlib:

Concatenating multiple CSVs to create a consolidated DataFrame using pd.concat.
Adding columns to enhance data representation.
Parsing cell data as strings for creating new columns using .str methods.
Employing the .apply() method for custom data manipulation.
Using groupby to perform aggregate analysis based on specific criteria.
Visualizing our findings through bar charts and line graphs using Matplotlib.
Adequately labeling and annotating our visualizations for clarity.
