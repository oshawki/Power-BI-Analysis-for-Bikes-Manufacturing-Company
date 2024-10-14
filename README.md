# Power-BI-Analysis-for-Bikes-Manufacturing-Company
A Manufacturing Company ; specialized in bikes & accessories; Headquarted in china ; wants to analyze its data collected from its sales stores located internationally.

Five Excel Sheets are provided
    • Sales
    • Products
    • Date
    • Region
    • Salesperson

Software Required for Analysis : Microsoft Power BI

Requirements:-
(1) Data Preparation & Cleaning
Data Upload
    • chose the proper connector and connect to all excel sheets and upload it to Microsoft Power BI data model

Using Power Query Editor
    • Use Power Query Editor to clean your data
        ◦ remove Null values
        ◦ remove duplicate entries
        ◦ replace empty cells with ( 0 ) value
        ◦ remove any extra spaces
    • Validate the Data
        ◦ all Quantity fields formatted as [ Decimal ]
        ◦ all Cost, Unit Price, total sales [ Currency ] [ Decimal ]
        ◦ all Date fields [ Date ]
        ◦ all text entries [ Text ]




Data Wrangling 
inspect Sales Excel sheet for :-
Quantity, Cost, Unit Price and total sales columns
    • remove any outliers found ( with documentation )
    • remove any annomilies found ( with documentation )

(2) Create Data Model
Data Model
use a STAR SCHEMA to build your model
Fact Table :-             Sales 
Dimension Tables :- Products - Salesperson - Date – Region

Establish a proper relationships with the proper common columns between Fact Table and each dimension table.

(3) DAX Analysis
create DAX formulas to calculate :-
Company Total Revenue
Total Sales by year
Total Sales for [Road Bikes] and color [Black]
NON-US regions Total Revenue


(4) Create Charts & Dashboard
Generate visuals and charts to demonstrate sales volumes report, trends, sales-person performance
visuals required :-
column charts - pie charts - line charts - 
Generate Insights
    • Company Total Revenue
    • Total Sales by Sales Manager
    • Top Selling products by category by year
    • Top Selling products by subcategory by year
    • Top Selling products by category by year for NON-US regions
    • Top Selling products by subcategory by year for NON-US regions
    • Top Performing Salesperson by year
    • Largest Sales by Country
