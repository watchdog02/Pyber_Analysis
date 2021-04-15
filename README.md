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
- There were 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the votes and 85,213 votes
    - Diana DeGette recieved 73.8% of the votes and 272,892 votes
    - Raymon Anthony Doane recieved 3.1% of the votes 11,606 votes
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 votes.
## Challenge Overview

## Challenge Summary


This Challenge consisted of adjusting the current script to include county statistics in the text file. These include which county got the most votes and the percentage of votes for each county. By adding a few new variables and dictionaries to record the data from election_results.csv, a similar if and for loops as the candidate variables can be used. 

This python script will pull data and create statistical information about any election results csv that has a header of Ballot ID, County, and Candidate in that order. It will give you a text file showing the county with the most votes, winning candidate and the percentage and count of votes for them. Should more data be aquired, the script could be adjusted to read more columns and analyze them. If you'd like a more visual format, graphs and charts can be made as well. 