
# Read Me
## US Flights 2008 Investigation
This file contains information about the contents and process behind each file in this report. 

## Dataset
This data consists of about 7 million flights that were scheduled to occur in the US during the year 2008. Various features describing each flight include scheduled and actual departure and arrival datetimes, origin and destination airports, distance traveled, cancellation details, and more. The dataset can be found [here](http://stat-computing.org/dataexpo/2009/the-data.html), with supplementary airport and carrier codes and other additional details found [here](http://stat-computing.org/dataexpo/2009/supplemental-data.html). 

## Summary of Findings
Beginning with the broad question of when is the worst time to fly, I quickly narrowed down my focus to cancelled flights and their associated characteristics. Although cancelled flights make up a small percent of the total 2008 flights (0.02% of that original 7 million), there were still over 130 thousand cancelled flights to investigate and compare to the successful 6.8 million. Throughout the exploration of correlations between cancelled flights and nearly all other characteristics available in the flight data, I found that cancellations had a strong relationship with only a few variables, which also had strong relationships with each other. The main cancellation contributors were month of the year, origin airport, carrier, and distance, with the leading cancellation codes being weather, carrier, and in part, NAS (National Aviation Service). 

Beginning with time of year, the most cancellations (and highest percentage of cancellations) occurred during winter months, with most cancellation codes pointing to weather (most likely severe snow storms or other wintery mixes). Next, I examined cancelled flights' relationships separately with origin airport, carrier, and distance. Combined with a little common sense, it became clear that there were also intermediary relationships between origin airports, carriers, and distance, such that location determines available carriers as well as potential destinations, which are directly related to distance from the origin airport. Each individual relationship with cancellations pointed to a slightly larger group of each field, while combining variables/relationships together narrowed in on origin airports that were particularly susceptible to bad weather and their associated carriers and distances (ie. possible destinations). 

## Key Insights for Presentation
For the presentation, I focus on the combination of winter, weather, location, and 'destination' to highlight the top indicators of cancelled flights. I introduced each variable separately, then narrowed in on the "worst case scenarios" by incrementally adding each feature together.

Once I introduce the worst, I bring back the successful flight data to remind the viewer that in the grand scheme of things, these cancelled flights still make up only a very small portion of all flights and that with a little foresight and common sense, could be easily avoided in similar situations in the future. Also, because this dataset only covers flights from one year, we cannot make any assumptions about predictions or yearly trends, but we can get a report of the past and a good idea of where to look in future broader analyses.



```python

```
