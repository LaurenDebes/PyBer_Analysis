# Pyber Analysis
Module 5-- Using Python Scripts using Pandas libraries, Jupyter Notebook, and Matplotlib. 
## Overview of Pyber Analysis
We are doing analysis for "Pyber", a Python-based ride-sharing app company. We performed analysis on CSV files with data about ride-sharing such as locations, dates, fares, etc. We were first tasked with creating several types of visualizations for the data that show the relationship between the type of city and the percentage of total fares and number of drivers/riders. Our analysis will help Pyber improve access to its services and determine affordability. We have now been asked to focus on data from 01-01-2019 to 04-29-2019 to make a multiple-line graph showing the total weekly fares for each city type.
## Pyber Analysis Results
**Differences in Data Between City Types:**
![PyBer_fare_summary.png](https://raw.githubusercontent.com/LaurenDebes/PyBer_Analysis/main/analysis/PyBer_fare_summary.png)
In general, the total rides, total drivers, and total fares in Urban Cities is the highest, followed by Suburban, then Rural type. However, when you divide the total fare by city type by total drivers in each type, the average fare per driver is actually highest in Rural areas. The average fare per ride follows a similar pattern.
Average Fare Per Driver:
  - Rural: $55.49
  - Suburban: $39.50
  - Urban: $16.57
  
 ![chartmodule5.png](https://raw.githubusercontent.com/LaurenDebes/PyBer_Analysis/main/analysis/chartmodule5.png)
 
**Pyber Summary:** Based on these results, I have three recommendations for addressing any disparities among the city types:
  - Best Option: Establishing a base wage for all employees. In Urban areas, although there are more riders, there are more drivers and often shorter distances leading to lower fares per ride. In Suburban and Rural areas, there may be a higher average fare per driver/per ride, but there are less rides in general. Establishing a base wage will make up for any disparities in the employee locations.
  - Another potential solution may be increasing the fare in Urban areas due to demand/ short distances. This would help even out the differences in average fares between the types of cities. However, this may not appeal to customers in Urban areas where they may then opt for a cheaper transportation alternative.
  - If reasonable, asking some drivers to go to a different city type as-needed to make up for unmet needs. Some Suburban areas get busier in April, and if Urban/Rural drivers live close enough they may be able to travel there to help with demand. This may also help Urban drivers recieve additional pay.
