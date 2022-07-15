# PyBer Analysis

## Overview
The objective of this project is to analyze ride-sharing data by city type (urban, suburban, rural). The data was pulled into a dataframe to summarize the information and a multi-line graph was produced to show the weekly fares by city type. 

##Results
The summary dataframe was produced using the below (dataframe) coding after *groupby* functions were used on the data to calculate the total rides, total drivers, total fares, average fare per ride, and average fare per driver for each city type.

![image](https://user-images.githubusercontent.com/107161421/179130525-7e5965fa-ea7a-4804-b747-c9e7cc807e27.png)

The data frame was then formatted to make the results easier to read using the below *format* codes and then the dataframe was complete.

![image](https://user-images.githubusercontent.com/107161421/179130702-ad2b21f0-d978-4a72-a47a-99113efeb96e.png)

The data frame shows urban cities have the highest total rides, total drivers, and total fares. However, rural cities have the highest average fare per ride and per driver. 

The data was then used to create another dataframe focused on the total fares per city type by date; specifically focusing on the time period of 2019-01-01 to 2019-04-29.

![image](https://user-images.githubusercontent.com/107161421/179131222-d82ba8e9-ba80-4184-b0a2-b513e1a7d6f0.png)

The dataframe breaks out each city types total fares by each week during the specified four month period. This is great information but is would be easier to understand and visualize in graph form. To accomplish this task the dataframe was used to create a multi-line graph using a *df.plot()* function.

![image](https://user-images.githubusercontent.com/107161421/179131465-de484c5e-fadd-4277-9997-b641f0ca4764.png)

The graph helps to illustrate the fare data for each city type- urban cities consistently have the highest fares, rural cities consistantly have the lowest fares, and interestingly all three city types had a slight spike in fares the last week of February. 

##Summary
Based on the findings in this study Pyber could take steps to resolve the disparities between their service in different types of cities.

The data shows that there are more drivers than rides in urban cities, almost double. Cutting back on the total number of drivers in urban areas could bring the average fare per driver up. The urban market is currently oversaturated with drivers and the average fare they are brining in is only $16.57 compared to $55.49 in rural areas and $39.50 in suburban areas. 

In rural and suburban areas there are more rides than drivers. If Pyber wanted to potentially increase the number of rides in these areas they could do so by having more drivers available and in turn lowering the average fare. This in combination with lowering the total drivers in urban cities could help to bring the ride fares for each city type closer together. 

Pyber could also consider digging into the data even further and conducting additional research to look into why the fares fluctuated in the different city types at the times they did based on the line graph. Uncovering trends during different times of the year in different areas could help them predict whether they need more or less drivers for an upcoming season and what kind of fares to anticipate. It may also be beneficial to look at the dates that all three markets align with their fare fluctuation; for example in the Jan-April 2019 period shown in the line graph all three city types had a spike in their fares near the end of February. If able to uncover the reason, in this case potentially Valentines Day but further research is needed, they would be able to plan their staffing accordingly and possibly plan strategic marketing campaigns targeted towards the specific event(s) to draw in more patrons. 
