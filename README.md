# Pyber_Analysis

## Overview of the Analysis : Purpose of the new analysis.

The purpose of the additional analysis is to uncover why there is such a stark difference between urban, suburban, and rural city types in total revenue generated. Our goal was to provide further visualizations that could inspire insight on the availabilty and affordablity of the ride-sharing services in different city types side by side.

We used Python, pandas, matplotlib, and Jupyter Notebook to produce the data and graphs during this study.

## Results
# 
![Pyber_fare_summary](https://github.com/LukeTaylorDS/Pyber_Analysis/blob/main/starter_code/Starter_Code/analysis/Pyber_fare_summary.png)

This multiple-line chart shows the total revenue by city type in the first third of 2019. The chart clearly shows that Urban cities earn far more than suburban and rural cities, not surprising due to the increased population in urban areas comparatively. 

![PyBer_summary_dataframe](https://user-images.githubusercontent.com/106044269/208990536-700961d9-d904-46ac-986d-f399af75f148.png)

This data frame shows that while urban cities earned more total revenue, the average fare per ride is larger in suburban and rural areas. This could be due to less total drivers in the rural and suburban areas in comparison to the amount of rides given. The urban city type has many more drivers per rides given, meaning the availability to a ride in an urban city could be directly linked to the lower average fares seen in the chart above. 

Trip distance, a data point missing, could heavily contribute to average cost being higher in rural and suburban areas. Assuming urban trips tend to be generally shorter than suburban and rural trip, this could account for the lower cost and increased use in urban areas. 

## Conclusion

In order to better understand the discrepancy in revenue between city types, I would recommend the following:
  1. Retrieve data on trip distance 
  2. Study rural and suburban markets to see if a higher total of drivers would lead to better availabilty and affordabilty, which could lead to an increase in demand in those areas
  3. Increase the amount of data points by analyzing the entire year, instead of just the first 4 months of the year, because we could be too zoomed in to see yearly and  seasonal trends
