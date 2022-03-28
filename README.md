# PyBer_Analysis

## Overview

This analysis seeks to determine weekly fares for the PyBer Company organized by city size for the months January through April, 2019. Our dataset includes two resources provided for analysis, city_data.csv and ride_data.csv, both found in the Resources folder. We have leveraged Pandas to read and organize our data, and Matplotlib to display our visualizations, all contained in a step-by-step Jupyter Notebook for presentation. All figures and visualizations can be found in the Analysis folder. 

With the data provided, our analysis seeks to find a relationship between city size - organized by Rural, Suburban, and Urban categories - and the weekly fares received over our given time period, in order to offer guidance on how to direct resources to bolster the level of service provided to customers by eliminating disparities between regions. 

From previous exploration of our datasets, we hypothesize that where distances between destinations are longer, such as Rural and Suburban locations, each ride will have higher average fare while total income for said regions will be lower than denser environments such as Urban locales. 

# Results

Our initial analysis sought to compare the total number of rides to the average fare in each city and group the results by the density of each city. We accomplished this by merging the data sets in Analysis/city_data.csv and Analysis/ride_data.csv. Using matplotlib, we constructed the following:

![Fig1, PyBer Ride-Sharing Data](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig1.png)

We can make several observations from this visualization. Cities qualified as urban, characterized by higher density and higher populations, had higher numbers of drivers in each city. Given the greater number of potential riders, the total number of rides also increased with city type. This progression is by no means absolute, the frontier between Suburban and Urban cities ranges from 9 to 27 rides per city. Much of this range can be attributed to the specific qualification of what makes a city "Urban" vs. "Suburban" or "Rural. Due to the greater number of rides in Urban areas, the average fare in urban cities does not vary as widely as in Rural areas. 

![Fig3, Ride Fare Data](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig3.png)

We can observe from this plot of fares grouped by city type that fares tend to be higher in rural areas, presumably where greater distances between destinations accounts for higher average fares. Urban cities have lower average fares, but many cities with high driver and rider adoption have average fares on par with the average rural locale. Coupled with the higher number of drivers, this accounts for a much larger share of PyBer's revenue than rural locations.

![Fig4, Driver Count Data](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig4.png)

Another examination of drivers by city type reveals that urban municipalities have a much greater range of driver adoption than rural cities. A small percentage increase in the number of drivers in an urban city accounts for entire rural cities worth of fares.  

![Fig5, Percent of Total Fares by City Type](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig5.png)

Indeed, Urban locales accountted for 62.7% of PyBer's total fares during the time period in question. Allocating resources to this most lucrative sector of PyBer's footprint would have greatest overall effect. In all cases examined so far, however, Suburban cities demonstrate a balance between the two extremes. They also demonstrate great potential for PyBer's continued growth.

![Fig7, Percent of Total Drivers by City Type](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig7.png)

While Urban cities account for a considerable portion of PyBer's total income, 80.9% of all drivers are concentrated in these locations. Suburban communities contributed a much larger share to PyBer's income with many fewer drivers. The average fare per driver was higher (see Ride Fare Data), and Fig 1 indicates that most Suburban cities with the same total number of rides as their Urban counterparts had much higher average fares. Encouraging driver adoption in PyBer's Suburban cities could yield significant long term gains. 

![Fig8, Total Fare by City Type](https://github.com/ipbrieske/PyBer_Analysis/blob/main/Analysis/Fig8.png)

We conclude with this graph to highlight the significant contribution Urban cities make to Pyber's income, as well as the potential of Suburban cities. While drivership in Suburbs was less than a quarter of Urban cities, the total income generated by Suburbs has been at times over half of that of Urban cities.

# Summary

From this analysis, we would offer three recommendations to grow PyBer's business

	1. Add more Urban cities to PyBer's portfolio. 
		- Urban cities account for a sizable percentage of PyBer's income. Adding access to another Urban location has an outsized impact when compared to a city qualified as Rural. 

	2. Encourage drivership in Suburban locations. 
		- Suburban drivers have generated a greater percentage of PyBer's revenue with a relatively smaller number of drivers. With higher average fares per ride, increasing the number of Suburban drivers would have a positive effect on PyBer's bottom line. 

	3. Incentivize longer trips in Rural cities. 
		- Rural cities may only account for a small percentage of PyBer's overall business, but still offer great potential. Rural locations show a tendency to have higher fares, a result of longer travel distances and times. Encouraging this type of customer behavior by reducing the fares for longer rides and increasing the fares for shorter rides would respond to current rider demand, thus increasing ridership and therefore overall fares. 
