# PyBer_Analysis

## Overview 
The purpose of this new analysis is to look at ride-sharing data by city type to determine any disparities that exist. The data was grouped by type of city (Urban, Suburban or Rural) so that we can assess the cost of our services and if certain factors play a role in the differences between them. By identifying differences between the three types of cities, we can use this information to guide business decisions for PyBer and where to focus resources. 

The ride-sharing data taken into account includes:
- Total number of rides per city type
- Total number of drivers per city type
- Total fares per city type
- Average fares per city type
- Average fares per driver


## Results
![Summary_df](https://github.com/Aleahkita/PyBer_Analysis/blob/main/summary_ride_share_df.png)
Urban cities had the most rides (1,625 total rides). This is 13 times more than Rural and 2.6 times more than Suburban total rides (which had 125 and 625 total rides respectively). 

A similar trend can be seen with the number of drivers which increases as you look from Rural (78 drivers) to Suburban (490 drivers) to Urban (2,405 drivers). However, the number of total drivers is less than total rides in Rural and Suburban cities, in the case of Urban cities there are significantly more drivers compared to toal rides. This points to a disparity between number of drivers and city type, possibly due to a higher/denser population typically found in Urban areas and a lower population in Suburban and Rural areas.

When looking at total fares, we see a stark difference between city types with total amount increasing from Rural to Suburban to Urban respectively. Urban cities make up the largest amount of total fares ($39,854.38), roughly 9.2 times the amount of Rural total fares ($4,327.93) and roughly 2 times the amount of Suburban total fares ($19,356.33). This difference seems reasonable taking the number of rides per city type into account.

Looking at average fare per ride, the highest average comes from Rural cities ($34.62) and decreases from Suburban ($30.97) to Urban($24.53). This difference could be due to a lack of drivers which increases demand for rides, thus increasing fare. It could also be affected by factors like distance, where a rural city might be more geographically spread out and trips might be longer.

When looking at average fare per driver, a similar trend occurs as seen in average fare per ride, where the highest average comes from Rural cities ($55.49) and decreases from Suburban ($39.50) to Urban ($16.57). This results from the stark difference in number of drivers per city type.


(insert image of multiple-line chart)
Looking at the line chart of total fare by city type, throughout the span of January through the end of April, there are similar patterns between city type that we see from looking at the summary DataFrame. Total fare increases from Rural to Suburban to Urban and is shown consistently in that order when compared weekly. 


## Summary
