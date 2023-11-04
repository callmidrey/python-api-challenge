# My Python API Challenge
This project consisted of two main parts WeatherPy and VacationPy

# WeatherPY
This section employed the use of API to download data and then analyse it. It was analyses and 12 image outputs were obtained. Refer to `WeatherPy/output_data`. The first 4 imageds ie Fig1-4 are general ones looking into the relationship between the latititude and othe factors such as Temperature, Humidity,cloudiness and Wind speed. Then the other images takes it a step further to provide a visula relationship of the prior analysis, dividing the world into two parts which is the Northen and southern Hemisphere. `only Temperature vs Latitude in the Northern Hemisphere and Wind Speed had a Negative relationship but with the priorbeing significant and the latter not significant`. All the other has a positive relationship which were not significant except Temperature vs Latititude in the Southern Hemisphere.

Relationship: A positive relationship means that as one variable increases, the other variable also tends to increase and vice versa. In the context of the Analysis, it can be said that in a positive relationship, as latitude (x-axis) increases (moving away from the equator), other variables dennoted by 'y-axis', i.e., Temperature, Humidity,cloudiness and Wind speed, tends to increase. This is often the case, as generally expect higher temperatures near the equator and lower temperatures as you move towards the poles and the opposite can be said to be true. 

R-Value (Coefficient of Determination): The coefficient of determination, denoted as "r-squared" (r^2), measures how well the variation in the dependent variable (dennoted by 'y-axis', i.e., Temperature, Humidity,cloudiness and Wind speed) can be explained by the independent variable (in this case, 'Latitude') using a linear regression model. A high r-squared value, close to 1, indicates that a large proportion of the variation in 'Max Temp' can be explained by 'Latitude.' In other words, if the linear regression line does a good job of fitting the data, and there is a strong linear correlation between the variables.

# VacatioPy
This is the second part of the project where the data downloaded earlier was plotted onto a map to have a visual representation of the locations. Then a filter was applied to create a data frame where an ideal condition was set and within 10000 meters within the area which meets the ideal requirement, a hotel name is printed as wwell as the city within which it is located as well as the country, not forgetting the location in terms of Longitude and Latitudes with a bonus of the ideal tempereature of the site.






