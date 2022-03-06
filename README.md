# PyBer Analysis

## Project Overview
> The project we have been assigned it to create a summary of the PyBer data by the city types of Urban, Suburban, and Rural and to show the metrics for total rides, total drivers, total fares, average fair per ride and average fare per driver. Once we have created the metrics, we then need to create a multi-line graph to display the weekly fares for each city type. Finally, we will summarize the results and present our recommendations

## Resources
* Data source: city_data.csv, ride_data.csv
* Software: Python 3.7.10, Anaconda, Jupyter Notebook

## Results

The analysis summarized the data into the three city types of Urban, Suburban and Rural and created metrics to show total rides, total drivers, total fares, average fare per ride and average fare per driver as seen in the below image.
![](https://github.com/timbialek/PyBer_Analysis_Mod_5/blob/main/Resources/pyber_metrics_summary.png)

* Rural Cities have the least number of riders, drivers and total fares but have the highest average fare per ride and average fare per driver.  In rural areas locations tend to be spread further apart which is probably driving up the average fare since the rides cover a longer distance and take more time.  The low ridership could be due to more people owning their own transportation since most places are probably not within walking distance.

* Urban Cities have the highest number of total rides, total drivers and total fares but they have the lowest average fare per ride and average fare per driver.  Since urban areas tend to be cities it would reason that most of these people are only going a short distance when they are getting a ride which is why the average fairs are so low.  The other issue with the urban setting is that there are more drivers than there are rides which contributes to the low fares per driver.

* Suburban cities pull in half the total fares that the urban cities do with significantly less rides.  This setting has a significantly higher average fare per ride and per driver than the Urban setting.  This seems like the ideal makeup of rides and drivers giving it a solid average fare per ride and driver when compared to the rural and urban settings. 

From the line graph below that shows the total fares per week by city type it can clearly be seen that the rural setting brings in the least weekly revenue while the urban setting brings in the most and the suburban setting is in-between.  While you can see the peaks and valleys on the graph, we would need to perform some additional analysis to determine what is driving the increases and decreases in the fares.

![](https://github.com/timbialek/PyBer_Analysis_Mod_5/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

>In reviewing the above analysis there appears the be a significant need to increase ridership in all settings which could probably be accomplished with a large marketing campaign. With a combined total of 2,375 rides in a 4-month period for 2,973 total drivers there is not nearly enough rides for the drivers that make-up the workforce.  The Urban cities suffers the worst from this issue since there are more drivers than rides in this setting.  There are 2,405 drivers for 1,625 rides, which equates to each driver only getting .675 rides in a 120-day period, which indicates there should be a reduction in the workforce until there is an increase in ride demand.  Next, I would recommend looking at the rural area to see if running a lower promotional price would help increase volume.  Given the low ridership we need to find a price point that works for this setting a testing out various promotional prices would be a good way to go about this.  Lastly, another consideration for the Urban setting would be to look at increasing the pricing to drive up the average driver fare to help balance out the fares for the drivers in each city type.
