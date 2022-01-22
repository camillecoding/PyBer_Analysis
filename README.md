# PyBer_Analysis

## Overview of the Analysis ##

In this analysis, my aim was to visualize trends in use and ride data for my client, a ride-sharing service. The ride locations were the first level of analysis, as the type of region where the user was located (either an Urban, Suburban, or Rural area) helped to determine other details of their ride. The original datasets also revealed the number of total drivers in each region and the total sum of all regional fares during this time period. My first level of analysis calculated the average fares by ride and the average fares by driver, subcategorized by the region where the fare occurred.  

## Results ##
First, I needed to organize this data into a DataFrame and sort by the necessary parameters. The graphic below reveals the app usage by several parameters. 

<img width="764" alt="Screen Shot 2022-01-21 at 8 46 54 AM" src="https://user-images.githubusercontent.com/95657458/150537661-c9f7dcef-e32b-4786-b258-34a5d9feb10b.png">

Naturally, usage in Urban areas is the highest of all three regions for both riders and drivers. As a result, the total fares are highest in this region. Likely due to the geography of most urban areas, the average fares per ride and average fares per driver are lowest of all the three cities. Urban dwellers tend to travel within their geographic location and urban areas tend not to be large in terms of mileage.

Rural areas had the smallest usage in terms of rides and smallest pool of drivers. Because rural areas tend to be largest, the average fares per ride and average fares per driver were the highest of the three regions. 

<img width="358" alt="Screen Shot 2022-01-22 at 11 11 31 AM" src="https://user-images.githubusercontent.com/95657458/150646562-e5f90816-2a35-4f06-8e31-7520dae38ac8.png">


The final stage of this project required that I prepare this data for visualization in a scatter plot. I aggregated this data to indicate total weekly fares from January though April 2019. The scatterplot below emphasizes changes in total fares over the 4 month period.

![Pyberfaresummary](https://user-images.githubusercontent.com/95657458/150646574-24c88d98-bbbc-40d9-8807-c2343a7bc18e.png)


## Summary ##

Based on these results, I provided three recommendations to this client. First, I recommended that the client targets rural areas to increase ridership by either reducing fares or incentivizing the existing drivers in the region to drive more frequently. Second, I recommended that this client caps the number of drivers in Urban areas from late February to the beginning of April. The fluctuation in weekly fares could be a result of new drivers entering the market or fewer riders using the app. In either event, limiting the number of drivers will allow this client to engage existing drivers more and potentially increase their take home pay. The final recommendation for this client was to provide Suburban rider incentives from March to April when the weekly fares flatten. Since riders in Suburban areas often have several transportation options, they will need incentives to elect to use this ride-sharing platform. This company could emphasize the environmental impact and the opportunity to meet more neighbors, since Suburban enclaves can be more isolated than cities. 
