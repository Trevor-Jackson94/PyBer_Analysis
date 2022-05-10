# Pyber Analysis
## Overview
Our analysis of ride sharing data across multiple city types was conducted to assess the usage and value found in the ride sharing data based on type of city: rural, suburban, and urban. We analyzed the raw data found in the city_data.csv and ride_data.csv files to gain insight into the differences in rides, drivers, fares, average fare per ride, and average fare per driver for each city type. We then created a pivot table to give in depth details regarding fares per week for each city type and plotted them on a line graph for comparison.

## Results
From the data we merged, cleaned, and ran some calculations to obtain the following summary DataFrame.

![Summary Data Frame by City Type](https://github.com/Trevor-Jackson94/PyBer_Analysis/blob/main/Summary%20DataFrame.PNG)

From this DataFrame a pivot table was created to better understand fare data and it's relationship with time for each city type. We used a .resample() function by week linked with the .sum() function on our pivot table to obtain a DataFrame showing the sum of each weeks fares in USD throughout the first quarter of 2019 for each city type. We then plotted the data on a single line graph seen here.

![Total Weekly Fares by City Type for Q1](https://github.com/Trevor-Jackson94/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

## Summary
Based on the summary DataFrame created, the pivot table, and the plot of the 'Total Fare by City Type' rural cities consistly perform poorly. The fares are very low, the average fare per ride is quite high, likely due to the distances covered in rural areas, and there are much fewer drivers compared to urban and suburban. My first recommendation would be to try and increase drivers in rural areas to attempt to capitalize off of the higher average fare prices since the driver count in rural areas is significantly lower with more ground to cover. There seems to be a saturation in drivers in urban areas as well, providing an incentive for urban drivers to move to the rural areas might benefit the company. I think expanding our ride sharing services to new small towns across the nation could benefit the company well and provide higher profit margins.
