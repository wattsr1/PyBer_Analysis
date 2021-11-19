# PyBer Analysis

## Overview

This project is looking at the data collected by the ride sharing company PyBer to observe trends on the ride data collected.  The goal is to provide the CEO with insight into ride revenue in different city times which include urban, suburban, and rural cities.  This data can help determine the strategies for the company moving forward on how resources are allocated and develop metrics that can be used to measure the performance of the drivers in each type of city environment.  To provide this analysis, the city data and ride data summaries were collected and merged to create an overview of the rides within a 4-month window.  These datasets were analysed using Pandas and JupyterLab to clean and sort the data to create visuals to represent the trends observed in the data. 

---

# Results

## City Type Analysis

Using the merged dataset, each city within the territory was characterized as being one of three city types: Rural, Urban or Suburban.  The data for each city was grouped by city type and allowed for the analysis trend on the rides conducted in each city type.  An overview of the data can be seen in the table below which gives a broad summary of the ride data that was collected for this analysis.

<img.src("Resources/PyBer_Data_Summary_Chart.png)>

### Urban City Type:

The data from the urban city types showed that there were a greater number of rides and overall ride revenue from these areas.  There is the largest number of drivers and the highest fare revenue observed from the rural cities. There is also the highest number of rides overall from the urban cities.  The urban centers also have the lowest average fare and the lowest average fare per driver. 

### Suburban City Types:

The suburban city types fall between the urban and rural city types.  They have a moderate number of drivers and rides and the average fare and average fare per driver falls between the rural and urban city types.  There is higher increase in the average fare per driver between the urban and suburban drivers, with the suburban drivers making 138% more per ride that that of the urban drivers.  This with only a 26% greater in average fares in the suburban cities versus the urban cities. 

### Rural City Types:

The rural cities have the lowest ride and driver numbers with the lowest fare revenue of the other two city types.  Conversely, the rural cities have the highest average fares and average fare per driver than the other areas.  The rural cities have 5x less drivers that the suburban cities and 13x less drivers than the urban cities.  The rural drivers however earn 234% more in average fares than the drivers in the urban centers with only a 41% greater average fare than their urban counterparts.  

### Overview of the data

From an analysis of the week-by-week rides from each of the city types, a line graph was created to show the relationships between the frequency of rides between each of the areas.  As seen in the figure below, there is a similar variation in the total fares collected from the rides across the rural and urban cities.  The suburban cities appear to have a more consistent number of rides over time.  This there is similar trends observed in late February across all the cities, but the overall trends appear unique to each area.  There is a consistency of the overall amount of ride revenue collected in each city type over time which is reflected in the overall rank of each city in the overall data. 

<img.src("analysis/PyBer_fare_summary.png")

A further analysis of the data using a scatterplot shown below, illustrates the clustering of the rides by city in comparison between the number of rides and the average fares.  This data set shows that there is a larger concentration of the rides in the urban city groups but a lower overall average fare per city.  There does appear to be some crossover between the number of rides between the suburban and urban city types however the suburban average fares are distinctly higher in this crossover area.  The rural city types are generally show a consistently lower number of rides and a consistently higher average fare.

<img.src("analysis/Average_Fare_by_Ride_Summary.png")

Finally, an analysis of the distribution of fares between the city types showed that there was a consistent range of fares between the urban and suburban city types, with a large range of fares observed in the rural city types.  This is illustrated in the boxplots that are shown below that present the distribution of the fares between the three city types. 

<img.scr("analysis/Boxplots_PyBer_Fares_per_city.png")

---

## Summary

Based on these findings the following suggestion for PyBer to help optimize the efficiency of the operations for each of the various city types.  From the data there are distinct characteristics observed between the three city types and the following suggestions are provided:

1. Urban City Types: These cities have a large volume of rides with a variable fare rate between rides.  The cities with the highest ride numbers also show the lowest average fares per driver.  This suggest that thought the volume is high the profitability for drivers is relatively low.  This is evident in the areas where the cross over between the number of rides and the average fare observed between the suburban and urban drivers.  This suggests that urban cities with rides per city of less than 25 may be oversaturated with drivers and they should look at reducing the numbers of drivers to increase the average fare per driver.  

2. Suburban City Types: These centers appear to show some optimized balance between number of drivers and number of rides with relatively moderate fares per ride.  This can make this a bit of a benchmark for the business.  There are however some centers with higher volumes of rides (between 20-30 ride/city) that show a low number of drivers which may be negatively affecting the efficiency of the rides in these centers.  There is a notable difference in the number of drivers in this range within the urban centers and suburban cities with a similar demand on rides. As the overall revenue of these centers is lower than the urban centers but the ride volumes appear similar to the urban centers there appears to be a growth potential within this region. These centers should be focused on to increase recruitment of drivers and an increase in advertising in these areas to boost revenue.

3. Rural City Types:  The rural city types have the lowest number of rides which may reflect the need or the demand for such services.  There is however a wide range of variability of the ride fares within these centers.  The average ride fare is much higher in these areas, but the demand is much lower.  Based on this, the centers with a low ride and low average fare must be carefully monitored to optimize the number of drivers servicing these centers.  For example, the city of Garzaport showed 3 rides over time frame which is serviced by 7 drivers. These areas could be a potential growth are however as there appears to be a demand in these centers, therefore an increase in the publicity of the service in these areas could help increase the use and potentially the revenue. 

