# **Overview of the Analysis**

Per the request, a new summary DataFrame was created using Pandas.  The original ride and city data was merged to created a DataFrame with all PyBer ride data and another Pyber Summary DataFrame was created showing the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver by city type of either Rural, Suburban, or Urban. A new pivoted DataFrame was created, indexed by dates, with a filtered time frame between 2019-01-01 and 2019-04-29.  The columns were made of the city type with the values made up of the total fares by week.  The summary of total fares by city type by date was then used to create a multi-line graph showing those fair totals by week.  The graph was created with MATPLOTLIB.

## **Results**

The Pyber Summary DataFrame shows that the Rural city type had the fewest rides, drivers, and total fares.  However, rural cities also had the highest Average Fare per Ride and Average Fare per Driver.  Urban city types were the exact opposite with the largest total of total rides, total drivers, and total fares.  Urban cities also had the lowest Average Fare per Ride and Average Fare per Driver.  The Suburban city types fell somewhere inbetween Rural and Urban.

![pyber_breakdown](https://user-images.githubusercontent.com/78942457/112754326-8c3d3a80-8fa9-11eb-9081-21f7d9aa9bff.PNG)

The results of the first quarter snapshot showing the total fares by week by city type suggest that the Urban cities tend to have fewer large jumps week to week in total fares, but when they do happen, they are more pronounced.  Rural cities had more variance week to week but the total amount of variance was smaller due to that city type having smaller totals any given week.  The Suburban cities appear to have less variance week to week, but does seem to have waves of highs and lows.  The one common theme between all three city types is there is a large spike of fares towards the end of February, potentially due to Spring Break.

![PyBer_fare_summary](https://user-images.githubusercontent.com/78942457/112755203-b09b1600-8fad-11eb-887b-061f1b36ddb7.png)

## **Summary**

I would recommend three new pricing initiatives in order to address the disparities and take advantage of specific opportunities.  
* **Peak Pricing**
  * Introduce adjusted fares based on number of drivers available and total number of rides being requested.  Higher pricing during busier times could help drive up the average fare per ride and driver while lower pricing could help driver the number of rides being requested which in turn could generate a greater need to the number of drivers needed.

* **Holiday Pricing**
  * As shown in the multi-line graph, it appears there is an increase in all cities at the end of February, possibly coinsiding with Spring Break.  With a large number of ride requests during those periods, a planned increase in fare pricing could help drive revenue in Rural areas and increase the average fare per ride and driver for Urban cities.

* **Subscription Rides**
  * Creating a subscription service where idividuals or even groups acting as a carpool could subscribe to a either a guarenteed ride for a specific route at the same time either every day or on specific days.  We could offer a reduced rate, however the guarenteed fare could help smooth out the peaks and vallies of the uncertainty of total fares.  This could also potentiall help reduce the number of drivers in urban areas.  If our drivers could potentially schedule out their days as oppposed to only working when it's busy, the large number of drivers wouldn't be necessary and the average fair per ride and driver could potentially increase.
