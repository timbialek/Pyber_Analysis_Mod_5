# PyBer Analysis

## Project Overview
> The project we have been assigned it to create a summary of the PyBer data by the city types of Urban, Suburban, and Rural and to show the metrics for total rides, total drivers, total fares, average fair per ride and average fare per driver. Once we have created the metrics, we then need to create a multi-line graph to display the weekly fares for each city type. Finally, we will summarize the results and present our recommendations

## Resources
* Data source: city_data.csv, ride_data.csv
* Software: Python 3.7.10, Anaconda, Jupyter Notebook

## Results

The analysis summarized the data into the three city types of Urban, Suburban and Rural and created metrics to show total rides, total drivers, total fares, average fare per ride and average fare per driver as seen in the below image.
![](https://github.com/timbialek/PyBer_Analysis_Mod_5/blob/main/Resources/pyber_metrics_summary.PNG)

* Rural Cities have the least number of riders, drivers and total fares however have the highest average fare per ride and average fare per driver.  Since rural area locations tend to be spread further apart that is probably driving up the average fare since the rides the rides take more time and cover a longer distances.  The low ridership could be due to more people owning their own vehicles since most places are probably not within walking distance.

* Urban Cities have the highest number of total rides, total drivers and total fares while also having the lowest average fare per ride and average fare per driver.  Since urban areas tend to be cities it most of people are only going a short distance when getting a ride which would be why the average fair are so low.  The other problem with the urban setting is that there are more drivers than there are riders which contributes to the low fare per driver.

* Suburban areas pull in half the total fares that the Urban areas do with significantly less rides.  This setting has a significantly higher average fare per ride and driver than the Urban setting.  This seems like the precise makeup of divers and riders giving it a solid average fare per ride and driver when compared to the rural and urban settings. 

From the line graph below that shows the total fares per week by city type it can clearly be seen that the rural setting brings in the least weekly revenue while the urban setting brings in the most and the suburban setting is in-between.  While you can see the peaks and valleys on the graph, we would need to perform some additional analysis to determine what is driving the increases and decreases in the fares.

![](https://github.com/timbialek/PyBer_Analysis_Mod_5/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

>In evaluating the above analysis there appears to the be a significant need to increase ridership across all settings, which could probably be accomplished with a major marketing campaign. With a total combined total of 2,375 trips over a 4-month period for 2,973 drivers in total, there is an insufficient number of rides for the drivers that make-up the workforce.  The Urban cities suffers more from this problem becasue there are more drivers than rides in this setting.  There are 2,405 drivers for 1,625 rides, which equates to each driver getting only .675 rides over a 120-day period, indicating that there should be a reduction in the workforce until ride demand increases.  Next, I would recommend looking at the rural area to see if running a lower promotional price would help increase ride volume.  Given the low percentage of ridership we need to find a price point that is enticing for this setting and testing out various promotional pricing campaigns might be good way to do this.  Finally, another consideration for the Urban setting would be to try raising the pricing to drive up the average driver fare to start balancing out the fares for the drivers in each type of city.
