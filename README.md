# Retail-Analysis-with-Walmart-Data

## Data Description:

Worked on Walamrt stores data, with **6435** rows x **8** columns, totalling in  **402.3+ KB** approximately. 

This is the historical data that covers sales from 2010-02-05 to 2012-11-01, in the file Walmart_Store_sales. Within this file you will find the following fields:

* Store - the store number
* Date - the week of sales
* Weekly_Sales - sales for the given store
* Holiday_Flag - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
* Temperature - Temperature on the day of sale
* Fuel_Price - Cost of fuel in the region
* CPI – Prevailing consumer price index
* Unemployment - Prevailing unemployment rate
* Holiday Events - Whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week



## Data Analysis:

Worked on the each feature and its impact on the weekly sales.

1. **Tempreature**:
* I created 5 bins/labels for temperature values, to make it easier in the analysis.   
* Visualized the relationship between the temperature and its impact in the sales, to discover that the highest rate of sales was between 20 and 40 degree.


 2. **Fuel Price**:
* I created 2  bins/labels for fuel values, to make it easier in the analysis.
* The Sales were at it's top when the fuel price was less than 3.5 , We can say that the highest sales were  when the fuel price was  less than the mean which is 2.4


3. **CPI (consumer price index)**: 
* Made a **Box plot**, to determine if there are outliers.
* Visualized the relationship between the COI  and its impact in the sales, The Majority of sales have a CPI greater than 180 , In other words Most of the sales have a CPI greater than the mean which is 185.



4. **unemployment rate**:
* The higher Unemployment rate , The lower sales.
* The majority of sales has an Unemployment rate betwwen 5 and 10 .






