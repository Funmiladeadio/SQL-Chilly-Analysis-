# SQL-Chilly-Analysis-

## Introduction 
This session is for Data Exploration using MySQL workbench. We a considering a schema called Chillydata.

## Problem statement 
-	Year / Month Sales Trends Visualization		
- Region Sales Totals by Year and % Change		
-	Average Month Sales by Product	
-	products with the highest profit 
-	Year by Supplier Sales

## Data Schema 
![](picture3.png)

### Tables, Columns and Data types 
![](Table_char.jpg)

## Data exploration
Observing the questions to be solve above it will be good to create a temporary table that contains all information needed to answer those questions just in a table. Values likely to be needed are the Order_date,Region, product_name, Sales_rep name, Sales(Price * Unit), Profit (price – cost).
#### Syntax:
![](Temptable.jpg)

#### Table View 
![](rtemptable.jpg)

### Task 1: Year / Month Sales Trends Visualization
**Syntax:**
![](task1.jpg)
Result:
![](Rtask1.jpg)

The above generate the above query generates the table used to create a visual chart using tools such as Tableau, excel… for visualization.
### Visual 
!{](V_montlytrend.jpg)

Task 2: Region Sales Totals by Year and % Change
Obvious that the sales growth from each region isn’t consistent. For CA region there was an increase in the first two years (2021 & 2022) but a decrease of -6.75% to the previous year in 2023 and for WA there was a decrease of -58.12% in the year 2022 and a pick-up increase in 2023 but revenue wasn’t up to that of 2021.

Task 3:  Average Month Sales by Product	
Above snapshot shows the syntax that result Average sales by product and will be better interpreted using visualization tools. 

Task 4:  products with the highest profit 
Eraser with product_id ‘2’ is the most sold product
 
Task 5:  Year by Supplier Sales
Chally seams to be the leading sales_rep

Sales summary 
Total sales, Total profit, No_of_Transaction. 
Conclusion and recommendation  
