# Weather and Vacation Analysis

## Summary:

In this analysis, we collected data of over 500 different cities around the world using citypy and API calls. With OpenWeatherMap API, we got the corresponding values of max temperature, humidity, cloudiness, and wind speed for each city. Once we got these variables from the API, we plotted each of them against the latitude using Matplotlib scatter plots. For more detailed analysis, we divided the dataset into two subsets: northern hemisphere and southern hemisphere. These analysis helps us to see if there is a difference between the north and the south.

In second part of the analysis, we concentrated on the analysis which will help us to choose the perfect vacation spot according to weather conditions. With the help of gmaps API, we plotted world map, mark each city that we gather in our analyses` first part. And we assigned the humidity levels of cities on the weights of markers. After that we create a subset of cities according to our weather preferences and find the nearest hotels on that cities and plot info boxes for the hotels on the map that we created previously. 

# Observations

* With the help of the linear regression analysis and the correlation graphs, we can see that in northern hemisphere, there are strong negative relationship between Temperature and Latitude (correlation coefficient -0.83). On the other hand, in southern hemisphere, the positive relationship between temperature and latitude is not that strong (correlation coefficient 0.51). When you go away from equator, the decrease in temperature is much more in Northern Hemisphere than the one in Southern Hemisphere.
* Although linear regression did not show any strong relationship between the latitude and the wind speed, by looking at correlation plot, we can say that wind speed is lower in cities that are close to equator than the cities further to equator. 
* Neither Humidity nor Cloudiness has strong correlation with latitude.
