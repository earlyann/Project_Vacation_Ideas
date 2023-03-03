This project consists of two Jupyter notebooks, WeatherPy and VacationPy, that use Python request to APIs to retrieve weather and location data for over 500 cities worldwide and visualize the results in a variety of ways.

### Project Overview
In WeatherPy, the openweathermap.org API is used to retrieve current weather data for a random selection of cities and the results are plotted on scatter plots to visualize the relationships between latitude and temperature, humidity, cloudiness, and wind speed. The script also performs linear regression analysis for each of these relationships and plots the regression lines on the scatter plots.

In addition, WeatherPy creates scatter plots specifically for the Northern and Southern hemispheres to visualize the relationship between temperature, humidity, cloudiness, and wind speed and latitude. Linear regression analysis is also performed for these relationships.

In VacationPy, the city data obtained in WeatherPy is used to create a heatmap that shows the location and humidity level of each city on a map. The size of the markers on the map is proportional to the humidity level.

Finally, VacationPy narrows down the city data to select cities with ideal weather conditions, including a maximum temperature between 22-28 degrees Celsius, wind speed less than 4.5 m/s, and zero cloudiness. The Geoapify API is then used to find the first hotel located within 10,000 meters of the ideal coordinates and add its name and country as additional information in the hover message for each city on the map.

### Methods Used
The project uses the following methods:

##### API requests: The openweathermap.org and Geoapify APIs are used to retrieve weather and location data for the cities in the dataset.
Data cleaning and preprocessing: The raw data is cleaned and transformed into a consistent format, and missing values and outliers are handled.
Exploratory data analysis: The data is visualized and analyzed to identify trends, patterns, and outliers. Statistical tests and other methods may be used to validate the findings and identify correlations.

##### Visualization: 
The data is visualized using matplotlib, seaborn, and other visualization tools to create scatter plots and heatmaps that showcase the relationships between different variables.

##### Linear regression analysis: 
Linear regression models are used to explore the relationship between weather variables and latitude, and to identify the factors that influence the weather trends.

### Technologies Used
The project uses the following technologies:

##### Python: 
The analysis is performed in Python, using libraries such as pandas, numpy, scipy, matplotlib, seaborn, and requests.

### Outputs
The outputs of the project include a series of scatter plots and heatmaps that visualize the weather and location data for over 500 cities worldwide. The scatter plots show the relationship between latitude and temperature, humidity, cloudiness, and wind speed, and include linear regression lines for each relationship. The heatmaps show the location and humidity level of each city on a world map, with markers sized according to humidity level. The output plots are saved to the output_data folder.

Author Lacey Morgan
Data sources: https://openweathermap.org/
