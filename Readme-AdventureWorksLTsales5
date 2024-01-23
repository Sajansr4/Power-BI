AdventureWorksLT2019.bak file is present in the MS SQL server. It is imported in Power BI for building report.
Additional dataset are also uploaded- "Wikipedia website" and "States" which are Excel Workbook.
Tasks performed in AdventureWorksLTsales5 :
-Changed the data category of the following:
    AddressLine1 to Address
    City to City
    StateProvince to State or Province
    CountryRegion to Country/Region
    PostalCode to Postal Code
-Added a new column FullAddress, which concatenates AddressLine1, City, StateProvince, CountryRegion, and PostalCode.
-Added a new column called LineTotal, which multiplies OrderQty with ListPrice, and made the format as Currency ($).
-Created a measure named TargetSales, which increases LineTotal in the Sales table by 2%.
----------------------------------COMBINING THE DATA----------------------------------------------------------------------------
-Created a new table called Sales by States by importing the States table
-Got data from the Wikipedia website to import the list of states in America
-Removed the last 26 rows
-Removed the first 3 Rows
-Set the first row as headers
-Removed all the columns except the United States of America and US USA 840 columns
-Changed the name of the table to States with Codes
-Renamed the United States of America to State Name and US USA 840 to State Code Long
-Merged this data with Sales by States, displaying only the State Code Long field
---------------------------------------VISUALIZATIONS-----------------------------------------------------------------------------
-Added a gauge chart with LineTotal in the value Properties and TargetSales in the Target value Properties
-Set the Max value of the gauge to 1460000, and named it as Target Sales
-Created a pie chart with CompanyName and LineTotal; named it as Top Selling Companies, and center-aligned it
-Created a stacked bar chart with MainCategory and OrderQty columns; named it as Sales by Main Category, and then, center-aligned it
-Clicked on Analysis, expanded the Constant Line, and clicked on Add. Then, set the value to 500, and change the color to Red
-Created a donut chart with MainCategory and LineTotal
-Named it as Sales by Main Category, and center-aligned it
-Created a stacked column chart and add Product, LineTotal, and MainCategory
-Filtered the products to display only those with sales greater than US$32,000, and then, filtered the list to display only ‘bikes’
-Named it as Top Selling Bikes, and center-aligned it
-Added a Constant Line, with the value set to 35000, and then set the color to Red
-Saved the report, and add a new page to the report
-Created a map visual with City and LineTotal, and named it as World Sales by City
-Added a map visual with State Code and SalesYTD, and renamed the map to Sales by State
****************************************************************************************************************************************