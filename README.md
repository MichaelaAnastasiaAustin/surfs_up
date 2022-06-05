# surfs_up

## Overview
The purpose of the analysis was to find temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources
- Data Source: hawaii.sqlite
- Software: SQLite, Python, Jupiter Notebook, Flask


## Results
Using Python, Pandas functions and methods, and SQLAlchemy, we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then, we converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics (see screenshots below).

June 

![June](https://github.com/MichaelaAnastasiaAustin/surfs_up/blob/main/June_Temps.png)

December

![Dec](https://github.com/MichaelaAnastasiaAustin/surfs_up/blob/main/Dec_Temps.png)

The summary statistics show us three key differences between June and December:
- the minimum temperature in December is eight degrees lower than the minimum temperature in June.
- the maximum temperature in June is only two degrees warmer than the maximum temperature in December.
- the average temperature in June is about four degrees warmer than the average temperature in December.

## Summary

All in all, Oahu's temperatures do not vary significantly between June and December. The average temperature of each month is only four degrees different. So, this means the surf and ice cream shop business would be sustainable year-round. Another important factor to consider is precipitation. So, I created two additional queries: precipitation data for June and precipitation	data for December.

June 

![June_precip](https://github.com/MichaelaAnastasiaAustin/surfs_up/blob/main/June_precip.png)

December

![Dec_precip](https://github.com/MichaelaAnastasiaAustin/surfs_up/blob/main/Dec_precip.png)

