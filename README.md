# PyBer Analysis
---
**DataSource:**  
  * city_data.csv
  * PyBer_ride_data.csv
  * Ride_data.csv 

**Tools:**  
  * Jupyter Notebook
  * Python/pandas/matplotlib
  * VS Code


## Overview

The intent of this exercise is to analyze four months' worth of ride sharing data to determine similarities and differences among rideshare programs in urban cities, suburban cities, and rural cities.  


## Analysis

Data was acquired in the form of .csv files. This data was merged and massaged for comparisons to be executed. Date information was transformed to datetime data type. Resample() and groupby() methods were used to put the data into a usable table for plotting. 
\

## Results

The analysis shows that urban cities brought in the money of the three types of cities throughout the four months of data. All three types had an uptick in revenue in about the third week of February with a similar lowering the first week of March. (Further study including weather data may show a correlation during this time frame.)  
\
The data showed while there were significantly more urban rides than suburban or rural, rural fares cost more on average than fares in the other city types and drivers in rural cities made much more per ride than other drivers, especially urban drivers. (If we were to introduce mileage data we would most likely see that rural rides were longer and therefore cost more.)  
\
The average fare per driver may be skewed. We cannot tell if drivers were counted at more than one city and as a result there may be an over count of drivers. As the numbers stand, urban drivers significantly outnumber the number of rides and almost 800 drivers who did not drive are figured into the average fare per driver number. This unknown method of counting drivers most likely affects all three city types.  


![PyBer_Summary_df_chart](https://user-images.githubusercontent.com/100614690/182543061-13cfd71a-82d0-4324-9f9a-db97cdf89ad2.PNG)

 
## Summary

Due to missing or unknown data it is difficult to make recommendations with certainty. It looks as though rural drivers are receiving higher average fares than urban or suburban drivers, however if mileage and gas consumption is taken into consideration the net revenue may be not as different. Because of the low ride count in rural cities, it is probably best to cap the number of drivers driving to keep their revenue higher. The CEO needs to reduce the number of urban drivers if the number shown in the data is accurate. The average fare per driver is too low to be economical. 
