# PyBer_Analysis
Analyis of the rideshare data from January to early May of 2019.


___
## Overview
### Purpose
The following data of the the total weekly fares for each city type was gathered and analyzed to provide the decision-maker(s) at PyBer with the knowledge/tools to help them make decisions on prioritization of resources for PyBer services.


### Executive Summary
The data provided herein provides a glimpse into the PyBer business model.  The data is constrained to only about 4 months worth of rides across various cities and city types (Urban, Suburban and Rural) but it can provide some insights into what steps can be taken next based on the analysis provided herein.


___
## Results
To make this analysis, the city_data.csv and ride_data.csv were joined and broken down to produce the following summaries using Pandas and corresponding Matplotlib library methods and functions:
- A table summary for average fares per ride and average fares per driver (in $USD)
- A multiple-line graph showing the total fares for each week by city type

### Ride-Sharing Data Summary
The following table outlines the PyBer data summary:
- The total number of rides for each city type
- The total number of drivers for each city type
- The sum of the fares for each city type
- The average fare per ride for each city type
- The average fare per driver for each city type

| **Table 1**. Total Weekly Fare by City Type |
| :---: |
| ![Summary Table per City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/Avg_fare_per_ride_or_driver_table.png) |

The data summarized in the table above can be further viewed in the following sections.


#### Number of Rides per City Type
The following chart summarizes the following:
| **City Type** | **Total Rides** |
| --- | :---: |
| Rural | 125 |
|Suburban | 625 |
|Urban | 1,625 |

![Rides per City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/Fig6.png)

Urban areas demand more rides than both of the other two areas combined.  This makes Urban cities an area where there are opportunities for growing the PyBer business.


#### Number of Drivers per City Type
The following chart summarizes the following:
| **City Type** | **Total Rides** |
| --- | :---: |
| Rural | 78 |
|Suburban | 490 |
|Urban | 2,405 |

![Drivers per City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/Fig7.png)

The data provides a clear message that the majority of drivers work in Urban areas.


##### Total Fares per City Type
The following chart summarizes the following:
| **City Type** | **Total Rides** |
| --- | :---: |
| Rural | $4,327.93 |
|Suburban | $19,356.33 |
|Urban | $39,854.38 |

![Total Fares per City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/Fig5.png)

As expected, urban cities will provide more total fares due to the higher demand in these areas.


#### Average Fare per Ride / per Driver per City Type
The data reveals a pattern where the average fare per ride trends upward in this order: Urban --> Suburban --> Rural.  This trend reveals that on average:
- **Rural** areas have the **highest fare at 34.62 per ride**.  
- On the opposite side, **urban** areas have the **lowest fare of $24.53 per ride**
- **Suburban** areas are revealed to **lay in between the other two city types at $30.97 per ride**



### Weekly Total Fares by City Type
The following table and Figure provide a glimpse of the weekly total fares (in $USD) per city type:

| **Table 2**. Total Weekly Fare by City Type |
| :---: |
|![Table 2. Total Weekly Fare by City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/Avg_weekly_fares_table.png)|

| Graphical View |
| :---: |
| ![Figure 1. Total Weekly Fare by City Type](https://github.com/mrmarken/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)|
| **Figure 1.** Total Weekly Fare by City Type|


The two graphics above provide a small glimpse of the weekly total fares per city type.  In the four month period (January 1, 2019 - April 28, 2019) analyzed, some upward trends in total fares are seen during late-February through mid-April.
However, it should be noted that additional data analytics should be performed across the various populations to better understand customer trends, driver satisfaction and overall business outlook.



___
## Summary

### Caveats
While the table above takes into consideration the total number of drivers per city type and provides an average fare per driver based on the total amount of fares per city type during the period of January 1, 2019 through May 8, 2019, it does not account for: 
- Those drivers that did not have any rides, or
- Drivers that had multiple rides 

If one assumes that each of the 1,625 rides in urban cities was performed by only one of the 2,405, then it would be expected that each driver had a similar average fare as the ride column. 
Conversely, for the 78 drivers in rural areas that completed 125 rides, it would be expected that some drivers completed more than one ride and even perhaps some completed no rides.  



### Recommendations
In conclusion, the following recommendations are made to the decision-makers:
1. To increase driver satisfaction and/or average fare per driver, you should consider increasing the per-mile charges in urban cities as these trips are likely are shorter than in suburban and rural areas.
2. Consider spending more time and resources to perform deeper dives into more precise analytics:
    - Is there any correlation between number of drivers vs. wait times in rural areas?
    - What is the true fare average per drivers for those that complete rides in each city type?
    - Understand customer needs by looking at total fares per week trends.  For example, we can see a slight in crease in the weeks starting in mid- to late-February and seemingly peaking toward the end of April.  It would be of value to understand market needs during these months and beyond.
3. Entice more people to join PyBer in rural areas to provide better service.

