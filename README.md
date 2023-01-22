# WeatherPy

WeatherPY:
Using the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code and then creating scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

These figures can be seen in the output_data folder

The plots are then separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude), which include the linear regression line, the model's formula, and the r-values.

# VacationPy:
VacationPy:
Using the Geoapify API and the geoViews Python library and to create map visualizations using the csv file generated in WeatherPy.
1. A map that displays a point for every city in the csv file is generated with the size of the point should be the humidity in each city.
2. The csv file is then created into a dataframe that is narrowed down to my preferences.
3. A new dataframe is created that stores the csv files cities, countries, coordinates, and humidity.
4. For each city, Geoapify API is used to find the first hotel located within 10,000 meters of the cities' coordinates.
5. The hotel name and the country are added as additional information in the hover message for each city on the map.

