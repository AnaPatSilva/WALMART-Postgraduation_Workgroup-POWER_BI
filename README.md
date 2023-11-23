![Image](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Walmart.jpg)
# Walmart (Postgraduation Workgroup)
# POWER BI

## My Intro
In the Data Analysis and Visualization Models module of my postgraduation we work essentially with Power BI.

And as an evaluation we had to create a group and make a report in Power BI of a dataset of our choice.

The name of our group was BI4Us.

## Dataset
To choose the dataset, we researched several options on Kaggle, choosing one about Walmart sales, because we felt it was the most in line with what we wanted to show in the report we had to make. ([Dataset](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Data/Walmart.csv))

## ETL (Power Query)
![Power_Query](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Images/Power_Query.jpg)

In Power Query we:
- Extract the original [dataset](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Data/Walmart.csv)
- Split the dataset into 3 tables
- Changed the data type of some columns (ig: Order ID, Order Date,...)
- Removed empty lines
- Replaced "." with "," in columns of type number
- Load to Power BI

## Relationships
![Power_Query](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Images/Relationships.jpg)

We related the dimension tables "tbl_Local", "tbl_Produto" and "tbl_Calendario" with the fact table "tbl_Orders".

## Report
![Report](https://github.com/AnaPatSilva/Walmart-Postgraduation_Workgroup-POWER_BI/blob/main/Images/Report.jpg)

In the report we display the following informations:
- Total Sales
- Total Profit
- Profit Percentage
- Number of Customers
- Bar chart with total sales and profit per month
- Bar chart with total sales by product category (with tooltip: product name and total sales)
- Top Product (name, number of units sold, total sales)
- Radial Gauge chart with percentage of variance between this year's and last year's sales
- Area chart with total sales per day
- Map chart with total sales by State (with tooltip: city and total sales)

Those informations can be filtered by:
- Year
- Month
- State
- City

## Conclusions
Our biggest difficulty was knowing what information was most important to display and placing it in an appealing and user-friendly way.
