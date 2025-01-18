# Datascience-Project
The problem statement revolves around predicting daily sales for multiple stores based on historical sales data, promotions, and other factors

Data Overview:
The data has been taken from Walmart Recruiting challenge on kaggle. Data Field contains a total of 4 datasets:

stores.csv

This file contains anonymized information about the 45 stores, indicating the type and size of the store.

Store: the store number  
Types: Types of the store  
Size: the size of the store  

train.csv

This is the historical training data, which covers 2010–02–05 to 2012–11–01. Within this file you will find the following fields:

Store: the store number
Dept: the department number
Date : the dates of sales
Weekly_Sales : sales for the given department in the given store
IsHoliday : whether the week is a special holiday week

test.csv

This file is similar to train file, except weekly sales

features.csv

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

Store: the store number
Date: the week
Temperature: the average temperature in the region
Fuel_Price: the cost of fuel in the region
MarkDown1–5: anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011 and is not available for all stores all the time. Any missing value is marked with an NA. CPI: the consumer price index
Unemployment: the unemployment rate
IsHoliday: whether the week is a special holiday week
