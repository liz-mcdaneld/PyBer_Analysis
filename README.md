# PyBer Analysis

## Overview of the PyBer Analysis
The purpose of this analysis is to review and analyze the PyBer ride-sharing company to showcase trends in different types of cities ride sharing data. The CEO has request to also show the total weekly fares for each city type by a multiple-line graph.

## Analysis Results
 To start the analysis the two dataset must be merged using the groupby() functions. I applied the groupby() function to get the: total rides, total drivers, total amount of fares, and the average fare per ride for each city type. 
 
 ![PyBer_summary_df](https://user-images.githubusercontent.com/103263248/173640529-e04b66e3-9562-4ef9-a111-0d8be02eb904.png)
 
Looking at this data frame we can see that:
•	Rural cities have the least number of drivers. The total fares are the least amount eared of the city types, the rural cities have the highest average fare per ride and average fare per driver.
•	Suburban cities land in the middle with a driver to rider ratio of 1:1.3. This places the suburban average fare per ride, and average fare per drive in between the low rural cities and high urban cities.
•	Urban cities have more total drivers than total rides. This also impacted the average fare per ride and fare per driver. While there are more Urban drivers, they have the lowest average fare per ride and earned considerably less.
At the request of the CEO, the data for the city types was turned into a pivot table to show the total weekly of the fares for each type of city. The dates were selected using the .loc() function to only show the data from January 1, 2019 through April 29, 2019. This data was then turned into a multiple-line graph to view the data.

![PyBer_fare_summary](https://user-images.githubusercontent.com/103263248/173640562-df182d7b-50c7-4dcc-bb72-86b1a17129bd.png)

Looking at this multiple-line graph we can see that:
•	All three cities have a peak in the end of February, before all three have the peak decline by the beginning of March.
•	Urban cities have a few more drastic peaks and declines throughout March.
•	Rual cities have another peak at the end of March before gradually declining throughout April.
•	Suburban cities have a small dip at the beginning of April before having a large uptake in fares.

## Summary
#### Based on the results my recommendations that can be given are below.
### 1. Rural Areas
Increasing the number of drivers in a rural area will allow more drivers to be available for rides. Due to the areas being rural we can assume that the rides given are often longer than in more densely populated areas. This means the turnover rate for drivers takes longer as well. Having a higher driver to rider ratio will also decrease the fares, making rides more affordable. With more available drivers and cost decrease this should encourage more riders to use PyBer Ride Sharing.
### 2. Suburban Areas
Suburban areas have the most dramatic and largest drop in fares of the three city types in the last quarter of February. To help this additional advertising or promotions around this time of the beginning of March could help boost rides. Another way to help boost rides and fares in the Suburban areas would be to increase drivers as well. 
### 3. Urban Areas
Urban areas have the lowest prices when it comes to fares. The ratio of drivers to riders is almost 2:1. Increasing advertising and promotions to increase rides will help attract new riders. Having a higher number of riders will help the drivers that are currently operating in these areas have a continuous stream of riders, providing more work and increase the amount of fares earned. 
Across all three types of cities there is a drop in sales in the last quarter of the month of February. To continue sales and increase rides promotional discounts, and advertising campaigns could be run. This would help all three city types by offering discounts to current users of PyBer Ride Sharing, as well as bring in new customers and increasing riders. 
