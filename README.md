# PyBer_Analysis

## Overview of the analysis

We have been hired as data analytics for PyBer, a Python based ride-sharing app and we will use the data collected by the app to create visualizations in order to make easier the communication of complex information quickly and clearly, enabling us to tell more compelling stories about the relationship that we find between the variables as type of city, the number of drivers and riders, average fares, etc. All the charts and visualizations will help the CEO of PyBer to improve the service and provide affordability for undeserved neighborhoods.

This final assigment includes the usage of Python, Pandas and Matplotlib to create a dataframe summary of the ride-sharing data by city type and a multiple-line graph to show the total weekly fares for each city type.

## Results

**Ride-sharing summary DataFrame by city type**

Using the merging data of the city_data.csv and ride_data.csv, the results are shown in the following table:


![Sharing rides](https://user-images.githubusercontent.com/106939511/179153706-c1121915-e503-4a1a-a8ae-72361f48615a.png)


Let analyze the results:

a) Total Rides: there is a huge gap in the number of rides between the different types of cities. The rural rides account for 20% of the total rides in the Suburban cities. The Suburban rides account for 38.5% of the total rides in the Urban cities. 

b) Total Drivers: there is a large discrepancy between the number of drivers per type of city. The total amount of Rural drivers are the 16% of the total amount of Suburban drivers. The Suburban drivers are the 20% of the total amount of the Urban drivers.

c) Average fare per ride: even the large discrepancies of the total rides and amount of drivers per type city, the price per ride is not assigned in the same proportion.  The Rural rides are a little expensive vs the Suburban rides by 10%. The Suburban rides are 20% more expensive than the Urban rides. Then the Rural cities pay more per ride than the Suburban or Urban cities.

d) Average fare per driver: when we look at the income per driver, it is clear to see a huge discrepancy again between the types of cities.The Rural drivers have 29% more income than the Suburban drivers. The Suburban drivers have 58% more income than the Urban drivers. Then the Urban drivers earn less per drive vs the Suburban and Rural drivers 

**Fare behavior by type of city in the first 4 months of 2019**

Using the merging data of the city_data.csv and ride_data.csv, pivot tables and  Matplotlib, the results are shown in the following line graph:

![Multiline graph](/analysis/PyBer_Fare_summary.png)

Let analyze the results:

- This graph shows the income made by the service from January to April of 2019. 

- The Urban cities make the biggest amount of money followed by the Suburban cities and Rural cities.

- The total fare remains fairly stable during the 4 months with a significant increase between February and March.

- The Urban fares have more ups and downs between March and April than other type of cities. 


## Summary and recommendations

1. Based on the first data summary chart is clear to see that the Rural cities are underserved but it is required to perform a market study in order to evaluate if it is really needed a fleet incremental. Usually these areas do not have much population but it is also required to understand if the amount of rides are not impacted by the fares per ride. It could be helpful to get/include the mileage per ride in order to have more clarity in the fare rate in future studies. 
2. The company should should pay attention to the low rate per driver. It could be helpful to do a market study and compare the rates of the same service on other platforms or the regular service to assess if the fare are not very low, which could lead to discomfort among drivers and, consequently, a deterioration in service.
3. In order to find the trends in the data and elaborate recommendations more assertive, it will be helpful to increase the dates range. For example, in that way we could confirm the months when the company would need to invest more in marketing to increase the fare.

