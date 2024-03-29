# python-api-challenge

WEATHERPY ANALYSIS
The task of this project was to pull random cities throughout the world and see if there are any statistical correlations between the city’s global latitude and conditions.  The variables examined in this analysis include:
•	City Name
•	City Latitude
•	City Longitude
•	Max Temp (in Celsius) 
•	Humidity
•	Cloudiness
•	Windspeed
•	Country
•	Date
547 randomly selected cities and their corresponding variable attributes were pulled from an API through OpenWeatherMap.org and put into a DataFrame for analysis.  A series of Scatter Plots were created to begin the statistical analysis.  The variables examined include:
•	City Latitude vs Temperature
•	City Latitude vs Humidity
•	City Latitude vs Cloudiness
•	City Latitude vs Wind Speed

CITY LATITUDE VS TEMPERATURE (Fig01)
When examining City Max Latitude vs. Temperature (2022-10-18) (Fig1) most of the cities in the study seem to be located between a latitude of -40* to 40*, representing 2760 miles above and below the earth’s equator.  The majority of the cities in the chart reside in a Temperature (C) range of 0 to 35 degrees Celsius (32-95 degrees Fahrenheit).  This result is not surprising as 32-95 degrees Fahrenheit is typically a comfortable temperature range for human beings.       

CITY LATITUDE VS HUMIDITY (FIG02)
While looking at City Latitude vs. Humidity (2022-10-18) (Fig2) the cities seem to be diversified across latitudinal coordinates, but a majority appear to reside in the 60-100% humidity range.  This graph shows a human tendency to gravitate to warmer climates with higher levels of humidity, but also outlines humans’ ability to adapt to a wide variety of latitudes and environmental environments.  This graph could also outline the need to expand latitude living locations as global populations continue to increase.
CITY LATITUDE VS CLOUDINESS (FIG03)
When examining City Latitude vs. Cloudiness (2022-10-18) (Fig3) there appears to be wide variability in the data encompassing the entire range of latitudes shown in the graph.  There does seem to be tendency toward the statistical extremes when looking at Cloudiness %, with a majority of the cities residing at the extremes of 0% and 100%.  When looking at the entirety of this graph it shows us that most cities reside in areas with very low or very high cloud cover and span a wide variety of latitudes.

CITY LATITUDE VS WIND SPEED (FIG04)
While looking at City Latitude vs. Wind Speed (2022-10-18) (Fig3) there appears to be wide variability in the higher city latitudes, but a tighter band of cities residing in the range below 6.5 wind speed(m/s). This result may not be all that surprising as a lower wind level would be more conducive to a wider range of outdoor human activities and be a positive addition to an overall living environment.      

TEMPERATURE VS LATITUDE LINEAR REGRESSION PLOT (FIG05 & FIG06)
When examining the linear regression plot of Temperature vs Latitude for the Northern Hemisphere you immediately can see a strong negative correlation showing higher city temperatures as the latitude nears the equator and lower city temperatures as the latitude moves away from the equator.  This linear regression appears to show a strong correlation with a definitive negative slope and an r-value of -0.883.  This correlation also makes intuitive sense as temperatures generally tend to rise as locations get closer to the equator and drop as locations mover further away.             
When examining the Linear Regression Plot of Temperature vs Latitude for the Southern Hemisphere we see a weaker positive correlation between higher city temperatures as the latitude.  This linear regression displays a more gradual positive slope and a weaker r-value of 0.517.  A potential explanation of the weaker linear regression seen in the southern hemisphere could potentially be due to a significantly smaller human population in the southern hemisphere vs the norther hemisphere, allowing southern hemisphere cities to be more spread out geographically. 

HUMIDITY VS LATITUDE LINEAR REGRESSION PLOT (FIG07 & FIG08)
The Humidity vs Latitude Linear Regression Plot for the Northern and Southern Hemispheres, both provided a low correlation in the results.  Both lineal regression plots show relatively loose positive correlations between city latitude and humidity, with a r-value in the north at .0457 and a r-value in the south at 0.384.  Neither of these polts show strong considerations for city location in relation to humidity, and it can be assumed that other environmental factors play a much stronger role in determining where a city is to be located.   
CLOUDINESS VS LATITUDE LINEAR REGRESSION PLOT (FIG09 & FIG10)
Upon examining Cloudiness vs Latitude Linear Regression Plots for the Northern and Southern Hemispheres both plots show very weak correlations between Cloudiness and City Latitude.  The linear regression plot for both the northern and southern hemispheres shows a gradual positive slope and a r-value of 0.304 for the northern hemisphere and a r-value of 0.271 for the southern hemisphere.  The graphs for both hemispheres point to a weak correlation between city latitude and cloudiness.      

WIND SPEED VS LATITUDE LINEAR REGRESSION PLOT (FIG11 & FIG12)
When looking that the Latitude Linear Regression Plots for Wind Speed vs City Latitude, both plots (northern and southern) show a very low correlation between the variables.  The plot for the northern hemisphere shows an almost horizonal slope with a r-value of 0.065 while the southern hemisphere plot shows a slightly negative slope with an r-value of -0.131.  Both plots display a very low correlation between city latitude and wind speed.
