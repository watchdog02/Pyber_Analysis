# Pyber_Analysis

## Project Overview
While working at a ride-sharing company, PyBer, I've been tasked with creating visualizations to show different metrics on how the compnay has been doing. These charts show things like changes in fares per driver or fares per ride in different types of cities.

1. Create DataFrames of the city types and create a bubble chart comparing the number or rides and average fare
2. Calculate summary statistics for the Number of Rides, Fares, and Number of Drivers per city and chart them in a box-and-whisker plot
3. Calculate the percentage of fares for each city type and create a Pie chart
4. Calculate the percentage of rides per city type and create a Pie chart
5. Calculate the percentage of drivers per city type and create a Pie chart
6. Determine which county had the most votes.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.8.8

## Summary
The analysis of the election show that:
- Urban cities have on average lower fares, but higher counts of rides compared to Suburban and Rural cities. Rural cities had higher fares, but less rides.
- Urban cities have the most driver numbers compared the Suburban and Rural cities
- Urban cities make up about 63% of all fares recieved. Suburban follows with about 30% and Rural trails with 7%
- Urban citis also lead with 81% of drivers
## Challenge Overview
This challenge consisted of using the same data and create a pivot table as a dataframe with the city types as the index and Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver as the columns. Once that had been created, a new dataframe was needed to create a line plot of the fares in different city types over time. The plot had to be easily ledgible and in the fivethirtyeight color scheme.
## Challenge Summary
To create the pivot tables, I first found the values I wanted and saved them in their own variables. Then I took them and created a dataframe with the same index; Rural, Suburban, Urban. From there it was some formating to make it look nice and the summary was ready to read. 
For the line chart, new dataframes had to be created using groupby of types and dates. From there, the pivot function helped in asigning date as the index, type as the columns, and the values as fare.Then the dates were to be condensed into weeks and then ploted to a line graph where some editing would make it easier to read.