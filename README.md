# python-api-challenge
06-Python-APIs Homework

Part I - WeatherPy

The following items were included in the final analysis of the data:

1. Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.

2. Performed a weather check on each of the cities using a series of successive API calls.

3. Included a print log of each city as it's being processed with the city number and city name.

4. Saved a CSV of all retrieved data and a PNG image for each scatter plot.

Part II - VacationPy

The following items were included in the final analysis of the data:

1. Created a heat map that displays the humidity for every city from Part I.

2.  Narrowed down the DataFrame to find my ideal weather conditions. Specs used:

          A max temperature lower than 80 degrees but higher than 70.

          Wind speed less than 10 mph.

          Zero cloudiness.

3.  Dropped any rows that don't contain all three conditions.

4.  Used Google Places API to find the first hotel for each city located within 5000 meters of my coordinates.

5.  Plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

