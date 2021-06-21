# W9-SQLite-SurfsUp

## Project Overview
The goal of this project was to perform an analysis of Hawaiin weather data to understand the possible impact of temperature on the profitability of a surf and ice cream shop. For this project we utilized Python, Pandas functions and methods, and SQLAlchemy. We also worked with a given data set in an SQLite file. In the results, I will compare the summary statistics for June and December.

## Results
For this project, I had access to weather measurements from multiple weather stations. The data set included measurements across multiple years and was indexed by date. In this analysis, I concentrated on understanding weather patterns for June and December. In order to extract the weather data for a given month, I utilized the sqlalchemy extract function to filter the month to June and December, converted the results into a list and then into a dataframe. Finally, I used the Pandas decribe function to get summary statistics for each month as shown below. 

**December Statistics** -------- **June Statistics**

![December_Statistics_Summary](https://user-images.githubusercontent.com/81983110/122693687-daf51c00-d208-11eb-88fb-e31ea01909b2.png) ------ ![June_Statistics_Summary](https://user-images.githubusercontent.com/81983110/122693688-daf51c00-d208-11eb-931d-f1ade1bd9f53.png)

### Key Observations:
1. There are more ~200 more observations for June than December which may introduce additional differences between the months. 
2. The standard deviation for June is lower (3.26 compared to 3.75) and in the interquartile range is smaller (4 degrees vs 5 degrees). 
3. The difference between the minimum and maximum for June is also lower (21 vs 27 degrees)

## Conclusions
From the results above, I concluded the temperatures in December are more variable than in June. However, based on the statistics, it appears that the minimum temperature in the December data (56) set is an outlier and that the majority of temparatures are within a few degrees of the range of temperatures observed in June. Based on this, we can confidentally say that temperatures are fairly consistent throughout the year and that a surf and icecream shop should expect to see business year-round, although with a slight dip around unusually cooler days in December. 
