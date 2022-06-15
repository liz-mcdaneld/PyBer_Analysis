# PyBer Analysis

## Overview of the PyBer Analysis
The purpose of this analysis is to review and analyze the PyBer ride-sharing company in different types of cities ride sharing data. The CEO has requested to also show the total weekly fares for each city type by a multiple-line graph.

## Analysis Results
 To start the analysis the two dataset must be merged using the groupby() functions. I applied the groupby() function to get the: total rides, total drivers, total amount of fares, and the average fare per ride for each city type. 
 
 ![PyBer_summary_df](https://user-images.githubusercontent.com/103263248/173900310-0235ce8b-741f-44e3-a037-ca1bcd9ce931.png)
 
Looking at this data frame we can see that:
•	Rural cities have the least number of drivers. The total fares are the least amount eared of the city types. The Rural cities have the highest average fare per ride and average fare per driver.
•	Suburban cities have a driver to rider ratio of 1:1.3. This places the Suburban average fare per ride, and average fare per drive in between the low rural cities and high Urban cities.
•	Urban cities have more total drivers than total rides. This also impacted the average fare per ride and fare per driver. While there are more Urban drivers, they have the lowest average fare per ride and drivers earned considerably less than the other city types.
At the request of the CEO, the data for the city types was turned into a pivot table to show the total weekly sum of the fares for each type of city. The dates were selected using the .loc() function to only show the data from January 1, 2019 through April 29, 2019. This data was then turned into a multiple-line graph to view the data.

![PyBer_fare_summary](https://user-images.githubusercontent.com/103263248/173900344-3712b4dc-2ec8-4c41-8008-0263840f60c7.png)

Looking at this multiple-line graph we can see that:
•	All three city types have a peak in the sum of fares in the end of February, then all three have the peak decline by the beginning of March.
•	Urban cities have a few more drastic peaks and declines in the sum of fares throughout March.
•	Rual cities have another peak at the end of March before gradually declining throughout April.
•	Suburban cities have a small dip at the beginning of April before having a large uptake in fares.

## Summary
#### Based on the results my recommendations based off the disparities between the city types are listed below.
### 1. Rural Areas
Rual areas have disparity in driver to rider ratio, at almost one driver to two riders. Increasing the number of drivers in Rural areas will allow more drivers to be available for rides. Looking at the other city types that have a higher driver to rider ratio average fare are lower. Based off this if Rual areas have a higher driver to rider the average fares cost should decrease, making rides more affordable. With more available drivers and a cost decrease, this should encourage more riders to use PyBer Ride Sharing.
### 2. Suburban Areas
Suburban areas have the largest drop in fares and customer usage of the three city types in the last quarter of February. To help this disparity, solutions to boost customer usage around the end of February to beginning of March should be considered. Another way to help boost rides and fares earned in the Suburban areas would be to increase drivers available for riders. 
### 3. Urban Areas
Urban areas have disparity of the lowest prices compared to the other city types when it comes to average cost of fares. The ratio of drivers to riders is almost 2:1. To balance this ratio, solutions to attract new riders should be considered. Having a higher number of riders will decrease the drivers to rider ratio. Which based off the driver to rider ratio data from the other city types, could balance out the average fare cost.  

