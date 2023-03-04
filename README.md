# Project: Vacation Ideas

Project: Vacation Ideas is a data analysis project that uses Python API requests to retrieve weather and location data for over 500 cities worldwide and visualize the results in a variety of ways. The project consists of two Jupyter notebooks, WeatherAPI and PlacesAPI, that take a data-driven approach to finding the best travel destinations based on weather conditions and hotel availability.

## Overview 

In WeatherAPI, we use the openweathermap.org API to retrieve current weather data for a random selection of cities, and visualize the relationships between latitude and temperature, humidity, cloudiness, and wind speed using scatter plots and linear regression analysis. The data analysis is complemented by exploratory data analysis techniques and statistical tests to validate the findings.

In the PlacesAPI notebook, we use the city data obtained in WeatherAPI to create a heatmap that shows the location and humidity level of each city on a map, as well as a map that highlights the best vacation spots based on your preferred weather conditions. To achieve this, we narrow down the city data based on a set of weather criteria, and use the Geoapify API to find the first hotel located within 10,000 meters of the ideal coordinates and add its name and country as additional information in the hover message for each city on the map.

### Methods Used
The data analysis in Project Vacation Ideas uses a range of methods, including:

API requests: The openweathermap.org and Geoapify APIs are used to retrieve weather and location data for the cities in the dataset.
Data cleaning and preprocessing: The raw data is cleaned and transformed into a consistent format, and missing values and outliers are handled.
Exploratory data analysis: The data is visualized and analyzed to identify trends, patterns, and outliers. Statistical tests and other methods may be used to validate the findings and identify correlations.
Visualization: The data is visualized using matplotlib, seaborn, and other visualization tools to create scatter plots and heatmaps that showcase the relationships between different variables.
Linear regression analysis: Linear regression models are used to explore the relationship between weather variables and latitude, and to identify the factors that influence the weather trends.

### Technologies Used
Project: Vacation Ideas uses the following technologies:
Python: The data analysis is performed in Python, using libraries such as pandas, numpy, scipy, matplotlib, seaborn, and requests.
Jupyter Notebook: The analysis code is written in Jupyter notebooks, with the results and visualizations saved to the output_data folder.
APIs: The openweathermap.org and Geoapify APIs are used to retrieve weather and location data for the cities in the dataset.

## Outputs
The outputs of Project: Vacation Ideas include a series of scatter plots and heatmaps that visualize the weather and location data for over 500 cities worldwide, as well as interactive maps that highlight the best vacation spots based on your preferred weather conditions. The data visualizations and interactive maps are saved to the output_data folder for your convenience.

Author Lacey Morgan
API links: https://openweathermap.org/ , https://apidocs.geoapify.com/
