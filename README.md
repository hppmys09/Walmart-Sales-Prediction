DATA SCIENCE PROJECT(taken from ph080 ,another repository of hppmys09)

WALMART SALES FORECASTING DATA SET :

INTRODUCTION:

1.Retail industry is a front-runner in the large scale employment of data science. Areas such as product placement, inventory management and customization of offers, are sought to improve constantly through the application of data science. Walmart is one such retailer.

2.train.csv and test.csv provides the information on historical sales of data of 45 stores of Walmart,features.csv,stores.csv, each of which having various departments. The goal is to predict the department-wise sales of each store using the historical data spanning across 143 weeks.


3.Walmart is also known for conducting promotional markdown events before major holidays such as Christmas, Thanksgiving, and Super Bowl among others. The difference between the weightage given to the data of regular weeks and the weeks including holiday seasons, coupled with unavailability of complete historical data, adds another level of difficulty of factoring the effects of the markdowns on the sales during the holiday weeks.

Predicting future sales for a company is one of the most important aspects of strategic planning. We would like to analyze how internal and external factors of one of the biggest companies in the US can affect their Weekly Sales in the future. 

Data Explanation

We had access to four different data sets from Kaggle.com about the company. These data sets contained information about the stores,departments,temperature, unemployment etc. We will explain each one of the data sets in more detail with each one of its features.
Stores:
- Store: The store number. Range from 1-45.
- Type: Three types of stores ‘A’, ‘B’ or ‘C’.
- Size: Sets the size of a Store would be calculated by the no. of products available in the particular store ranging from 34,000 to 210,000.
Train: 
-Date: The date of the week where this observation was taken . -Weekly_Sales: The sales recorded during that Week.
-Store: The store which observation in recorded 1-45.
-Dept: One of 1-99 that shows the department.
-IsHoliday: Boolean value representing a holiday week or not.
Features: -Temperature:Temperature of the region during that week.
-Fuel_Price: Fuel Price in that region during that week.
-MarkDown1:5 : Represents the Type of markdown and what quantity was available during that week.
-CPI: Consumer Price Index during that week.
-Unemployment: The unemployment rate during that week in the region of the store.

4.This model tries to achieve an approximate weekly sales prediction looking at previous years performance per Store on a weekly basis.

5. The data collected ranges from 2010 to 2012, where 45 Walmart stores across the country were included in this analysis. It is important to note that we also have external data available like CPI,Unemployment Rate and Fuel Prices in the region of each store which, hopefully, help us to make a more detailed analysis.

6.It is a regression analysis problem.

7.http://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

PROGRAM COMPILED  FOR THIS PROJECT:

The whole program is written with the use of python language.








