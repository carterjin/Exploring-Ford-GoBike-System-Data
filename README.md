# Ford GoBike System Data Exploration

## Dataset

The data is from the Lyft's Bay Wheels's trip data, which is publicly available, and can be found on this website:

https://www.lyft.com/bikes/bay-wheels/system-data

The data consists of 5618612 entries of bike rental information from July 2017 to Feb 2020, can still updating. Each trip includes the following information: trip duration, start and end time, start and end station name and corresponing locations, bike ID and user type (whether a subscriber or a casual customer).

## Summary of Findings

In the exploration, I find that the bike rental stations are in three seperate areas: San Francisco, Oakland and San Jose. The most bike rentals are in San Francisco, consisting of 75.7% percent of the total rents. Most people rent bike for a duration of about 10 minutes. Subscribers rent much more frequently than casual customers. People rent bikes more often in weekdays than weekends, and the most frequent rent in a day is around rush hours at 7 - 9 am and 4 - 6 pm.

A more detailed look of the rental information in San Francisco shows that most rentals happen near the south-east coastal areas, while the rental station to the west in the park and the rental stations to the south away from the financial areas near stony hill are much less visited. There is a positive correlation and linear relationship between rent duration and travel distance. The data also indicates an average traveling speed of 12km/h between rent and return.

I find that in general the amount of rentals are increasing over time, but rental numbers decrease drastically every christmas. I also find that travel between cities are extremely rare Also, subscribers in general tends to rent for a shorter period compared to casual customers.

## Key Insights for Presentation

For the presentation, I choose to focus on the question people probably most interested: who, where and when do people rent bikes the most? I start by showing the amount of rentals in each area by overlaying the position of rentals on the map. Then I show the percentage of rents from each area, from subscribers or customer, the proportion of rent in each day of week, and for each hour of day. Then I show a zoomed in figure that shows the exact rental stations in San Francisco and their rental frequencies, and the relation between rental time and travel distance in San Francisco.
