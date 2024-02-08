I just completed a challenge that involved two parts: WeatherPy and VacationPy. 

## Part 1: WeatherPy

In this part, I used the OpenWeatherMap API to retrieve weather data from a list of cities. The main goal was to create plots showcasing the relationship between weather variables and latitude. 

I created scatter plots for the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Each of these plots helped to visualize how weather conditions change as we move across different latitudes.

Furthermore, I computed linear regression for each of these relationships, separately for the Northern and Southern Hemispheres. This allowed me to quantify the correlation between each pair of variables and understand how strongly they are related.

## Part 2: VacationPy

In the second part of the project, I worked on creating a map that displays a point for every city in the city_data_df DataFrame. I then narrowed down this DataFrame to find my ideal weather condition.

For each city in the narrowed-down DataFrame (hotel_df), I used the Geoapify API to find the first hotel located within 10,000 metres of the city's coordinates. I added the hotel name and the country as additional information in the hover message for each city in the map.

This part of the project was particularly exciting as it combined data analysis with real-world applications, helping to plan a vacation based on preferred weather conditions.

Overall, this project was a great opportunity to apply and enhance my data analysis skills, particularly in working with APIs, data visualization, and linear regression.
