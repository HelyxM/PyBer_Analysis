# An Analysis of PyBer's Ride-Sharing Data

### PyBer Performance By City Types Main File:
[PyBer_Challenge](PyBer_Challenge.ipynb)

#### *Initial Analysis Notebook File*:
[PyBer_Analysis](PyBer_Analysis.ipynb)

#### PyBer CSV Datasheets:
- [city_data](Resources/city_data.csv)
- [ride_data](Resources/ride_data.csv)

## **Overview**:
It would be a fair expectation that a ride-share business's success varies based on the population density and level of urban development present in whichever location the business operates in. Based on this expectation, an analysis was conducted to test the validity of this theory and to measure the extent of the theory's accuracy or inaccuracy based on the data from locations in different states of urban development. By applying the tools available from Python and Pandas within the Jupyter Notebook application, it was possible to create a visual presentation of this analysis and to determine the results from a single image comparing the analyzed data values.

## **Results**:
The results of this analysis clearly show the theory considered at the start of this analysis was correct, and the success of the ride-sharing business PyBer is strongly affected by the degree of urban development present in the locations that the business operates. Not only did this analysis conclude that this theory was accurate, it concluded this accuracy with calculated values that distinctly show the trend between weekly fare sums paid by the customers over the course of several months, and the difference of fares paid between the levels of urban development. As shown in the chart below: the "Rural" location type had weekly fares that barely reached a high at the $500 level, while the "Suburban" and "Urban" types had fares that varied at a range of nearly $1,000 between their respective highest and lowest values. Despite this variance, though, the "Suburban" and "Rural" location types had values that consistently were around $1,000 difference between their data points. This meant the level of urban development had enough of an impact to clearly show the performances without anything close to an overlap and showed with each location's urban development type there was an increasing $1,000 improvement as they became more urbanized.

### *Weekly Fare Totals by City Type Chart*:
![PyBer_city_fare_summary](analysis/PyBer_city_fare_summary.png)

In addition to the trends shown in the chart based on weekly fare totals, a summary table of the values related to the levels of urbanization was also created and uses a more simplified approach to show the dramatic overall income differences between the different city types.
### *PyBer Summary Table*:
![PyBer_summary](analysis/PyBer_summary.png)

## **Summary**:
The trends in the data among the different city types include a variety of factors that can influence the performances of PyBer operations in each city type. Some disparities could be characteristic of locations with different levels of urbanization and others can be caused by unrelated circumstances. To better assist the practicality of applying this analysis to the business, a small list of disparities in the results is included below along with potential factors that can cause these disparities.
### *Recommendations*:
1. In the PyBer summary table, the "Average Fare per Ride" and "Average Fare per Driver" have an inverse relationship with the level of urbanization of each city type, and yet the "Total Fares" has a dramatic direct relationship with the level of urbanization. This is certainly due to the increase in customers requesting rides that offsets the lower cost in the average fare for those customers and the greater number of drivers available to provide rides allowing them to have a lesser sum of fares paid per driver but more rides overall offsetting that difference.

2. Another disparity is a trend on the PyBer summary table, where the "Average Fare per Driver" is greater than the "Average Fare per Ride" in both the "Rural" and "Suburban" city types but is reversed in the "Urban" city type's case. This is likely due to customers using specific drivers more frequently than others and some drivers having a greater sum of fares paid to them than others, causing an unbalanced spread among the different drivers for their fare totals. This could be due to customers having a preference for specific drivers or a trend where certain drivers are more often available for specific popular routes than others. When it comes to the density of the population of customers and drivers in the urban locations, this trend likely reverses because the increase in drivers is enough to spread out across all routes more equally.

3. One final disparity to note is in addition to the previous cases above contributing to greater profits in urban areas, the lower number of rides in more rural areas can be related to a greater ownership of personal vehicles among the populations in those areas and a greater expectation to drive themselves among those populations. This could potentially explain the reason for not just a lower concentration of rides and higher cost fares, due to those taking requesting such rides not having any alternative choices for long trips, but also the consistency of fares among the rural areas. The general theory is: for a greater variety of travel choices in an area, then the frequency of ride-share requests would vary, whereas if the variety is less, then the ride-share performance would be more consistent.
