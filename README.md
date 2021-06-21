# W9-SQLite-SurfsUp

## Project Overview
The goal of this project was to perform an analysis of Hawaiin weather data to understand the possible impact of temperature on the profitability of a surf and ice cream shop. For this project we utilized Python, Pandas functions and methods, and SQLAlchemy. We also worked with a given data set in an SQLite file. In the results, I will compare the summary statistics for June and December.

## Results
For this project, I had access to weather measurements from multiple weather stations. The data set included measurements across multiple years and was indexed by date. In this analysis, I concentrated on understanding weather patterns for June and December. In order to extract the weather data for a given month, I utilized the sqlalchemy extract function to filter the month to June and December, converted the results into a list and then into a dataframe. Finally, I used the Pandas decribe function to get summary statistics for each month as shown below. 
