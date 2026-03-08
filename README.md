# Weather-API-Collection
Write a script that fetches the current weather data for a given location from an API, such as OpenWeatherMap. The script should also display the data in a user-friendly format, such as a table or a chart. Alternatively, write a script that compares the weather data for two or more locations and displays the differences.

Author: Josiah Reinholz

Installation Steps:
    pip install tabulate

Enviornment:
    -uses free API key for OpenWeatherMap. API key can be switched to a personal key. A paid OpenWeatherMap key is not needed.

    - uses "https://api.openweathermap.org/data/2.5/weather" for the base url. This is the newest OpenWeatherMap call for the current weather at a given position

Description:
    Will ask the user to input either a city name or longitude/latitude coordinates. The appropiate type of API based on the type of location information given by the user.

    To display a meaningful table to the user I make nested lists for each valuable data point. Tabulate is used to turn the list of all features into a readable table.