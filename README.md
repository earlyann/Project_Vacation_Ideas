Module 6 - Python API Challenge

This activity has two deliverables, WeatherPy and VacationPy.

WeatherPy is a Python script calling https://openweathermap.org/api to generate and visualize the weather of over 500 cities of varying distances from the equator.

WeatherPy creates a series of scatter plots (shown in the output folder) to showcase the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

The WeatherPy script then computes the linear regression for each of those relationships. 

Finally, WeatherPy creates a series of scatter plots specific to the Northern (greater than or equal to 0 degrees latitude) and Southern (less than 0 degrees latitude) hemispheres showing the folling relationships including the linear regression, the model's formula, the r values and the explaination of what the linear regression is modeling. 

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude


VacationPy then picks up using the city data that was created in WeatherPy to create a map that displays a point for every city. The size of the marker in the map is relative to the city's humidity.

Next, VacationPy narrows down the city data to my ideal weather conditions:
- A max temperature lower than 27 degrees but higher than 21
- Wind speed less than 4.5 m/s
- Zero cloudiness

Finally, VacationPy use the Geoapify API to find the first hotel located within 10,000 meters of my ideal coordinates and adds the hotel name and the country as additional information in the hover message for each city on the map. The maps created in VacationPy are also saved to the output folder.
