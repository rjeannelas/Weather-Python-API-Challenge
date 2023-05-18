# Weather-Python-API-Challenge

### What is the weather like as we approach the equator - how would you prove that?

#### Part 1: WeatherPy
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator

Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere and Southern Hemisphere

- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

 #### Part 2: VacationPY
 Use the Geoapify API and the geoViews Python library to create map visualizations for future vacations
 
 - Create a map that displays a point for every city in the Dataframe
 - Narrow down the DataFrame to find your ideal weather condition
 - Create a new DataFrame to store the city, country, coordinates, and humidity.
 - Use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates
 - Add the hotel name and the country as additional information 
