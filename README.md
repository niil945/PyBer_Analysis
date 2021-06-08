# PyBer_Analysis

## Project Overview
Utilizing provided data create a summary DataFrame of the ride sharing data by city type and visualize that data to assess differences in fares. Analyze results to ascertain solutions to disparities in fares.

1. Calculate the total rides by city type
2. Calculate the total drivers by city type
3. Calculate the total fares by city type
4. Calculate the average fare per ride by city type
5. Calculate the average fare per driver by city type
6. Create a summary DataFrame showing data by city type
7. Calculate the fares by week per city type
8. Filter the data to show only rides taken between Jan 1, 2019 and April 29, 2019
9. Visualize the fares by week per city type for the filtered date range

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7, Anaconda 4.10.1, Jupyter Notebook 6.3.0

## Results
The analysis of the dataset show:
  - 3 categories of city types: Rural, Suburban, and Urban
  - Rural summary results are:
    - Total Rides: 125
    - Total Drivers: 78
    - Total Fares: $4,327.93
    - Average Fare by Ride: $34.62
    - Average Fare by Driver: $55.49
  - Suburban summary results are:
    - Total Rides: 625
    - Total Drivers: 490
    - Total Fares: $19,356.33
    - Average Fare by Ride: $30.97
    - Average Fare by Driver: $39.50
  - Urban summary results are:
    - Total Rides: 1,625
    - Total Drivers: 2,405
    - Total Fares: $39,854.38
    - Average Fare by Ride: $24.53
    - Average Fare by Driver: $16.57

[City Type Summary](Resources/summary.PNG)
[Total Fare by City Type Plot](Total_Fare_by_City_Type.png)

The differences in city type show that:
  - There are 5 times more rides taken in Suburban areas and 13 times more rides taken in Urban areas relative to Rural areas.
  - There are 6.2 times more drivers in Suburban areas and 30.1 times more drivers in Urban areas relative to Rural areas.
  - The total fares generated is 4.8 times more in Suburban areas and 9.2 times the total fares relative to Rural areas.
  - Fares by ride per city type decreased 11.5% in Suburban areas and 29.2% in Urban areas relative to Rural areas.
  - In Rural areas there are 1.6 rides per driver compared to 1.2 rides per driver for Suburban drivers and 0.68 for Urban drivers. 

## Summary
The difference in number of drivers, fares, and rides shows potential solutions for disparities in these markets. 

There are two indicators of PyBer service being impacted by a lack of drivers. The increased average fare by ride and by driver relative to the total number of drivers available implies that this may be an area to target for improvement. Additionally, both rural and suburban areas have less drivers available than the number of rides taken, with a more than 100% increase in average fare by driver from urban to suburban and more than a 200% increase between urban and rural areas. Targeted campaigns to promote the sign up of drivers in these areas may result in improved service in these areas, adding rides that would otherwise have utilized other services due to driver unavailability or high fares.

Consequently, the fare dropping by driver dramatically in urban areas with more drivers than total rides might be part of the solution by incentivizing urban drivers to target nearby suburban and rural areas for service, which could have the beneficial impact of lightening the service load on drivers in those areas while improving the fares of drivers working outside of their immediate area.

Additional studies of populations, travel time, and fares may be insightful to assess a target number of drivers for the different areas and how service usage varies to maximize service usage and utilization of drivers.


resulting in potentially untapped customer base due to service limitations from a lack of drivers.  that also result in higher individual fares that may also push away consumers. have an The limitation of drivers and consequently higher fares may result in less people utilizing PyBer in rural areas than would otherwise PyBer, particularly in light of the . Performing further analysis on city population versus drivers may provide insight on a target number of drivers for each area to maximize utilization of PyBer services and a pricepoint which would result in an in
