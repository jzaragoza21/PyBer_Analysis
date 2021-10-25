# PyBer_Analysis
Click here to view my code steps for this challenge: [PyBer_Challenge](https://github.com/jzaragoza21/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Overview of Analysis

The Pyber Challenge requires us to write and execute code for the following two deliverables: 1) using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type and 2) using our Pandas skills and two new functions, pivot() and resample(), create a multiple-line graph that shows the total fares for each week by city type. Subsequently, I delivered a written analysis below with a rideshare dataframe by city type and the results in differences in costs between urban, suburban and rural rides. Additionally, the written analysis provides three recommendations to the CEO for addressing any disparities among the city types.

## Results

The dataframe below breakdown ride share data by city type. City types are defined as rural, suburban and urban. The analysis further breaks this down by how many total rides and total drivers there are in each city type. Furthermore, we see the average fare for each ride and each driver is in the aforementioned city types. There is a clear correlation and perhaps even causation, between the population of a city and town and the number of total drivers and total fare and this therefore impacts the average cost per ride and per driver. In this case, the higher the population of a city or town, then the more drivers there are and the lower the fare per ride and per driver. The rural ride share economy reflects what economics describes as the law of supply. The less drivers there are because there is less of population to serve, also impacts the cost, in that there is an upward slope with cost. In short, the less drivers there are, the less acessible the product is, thus the higher the cost (or fare in this case) is.  


![RideShare Dataframe](https://github.com/jzaragoza21/PyBer_Analysis/blob/main/analysis/Deliverable1_RideShare_Dataframe.png)


In executing a multiple-line graph, we visulize the ride share data through 4 months: January 2019 to the end of April 2019. The first thing that stands out is that regardless of city type, they experience roughly the same fare trends through these 4 months. For example, rural, suburban and urban all experience a relatively large upwards trend in fares in the middle of February to late Februrary. Having said that, there is one noticeable outlier between the city types. Specifically, surburban fares almost double in early April, whereas both urban and rural fares drop in early April. 


![PyBer_Fare_Summary](https://github.com/jzaragoza21/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


## Summary

The analysis, dataframes and graphs above provide us with a solid foundation of data to build business operations recommendations on. The recommendations list is as follows:

  1. The outlier of suburban fares increasing while both urban and rural markets dropping during early April should be further studied. We are only examining four months of one year but as CEO I would want to know if this a trend that happened before and/or continued afterwards. As a result, I would invest in having the data science do a deeper analysis. This could result in deploying more drivers to suburban areas this time of the year or it could be determined that this was an anomoly.
  2. Given that the rural fare per ride is relatively close to urban and surburban fare per ride, yet rural's fare per driver is exponentitally more costly than its city type counterparts is cause for concern - or at least further study. We recommend diving deeper into the data here and see if more drivers are needed in rural markets. Given that wages are typically lower in rural markets, if additional analysis shows that adding a few more drivers could not only add more access for rural customers but it also would expand their reach and perhaps even expand their profit margins.
  3. Lastly, we would recommend further examining the ride share fare data for middle to late Februrary, when all three city types experience an increase in fares. Further analysis could show that this is a trend that happens annually and a time in which all markets need additional drivers. And if this is the case, then if PyBer's demand increases during this time, then adding more drivers could decrease customers wait times for drivers, and ultimately increasing customer satisfaction.

