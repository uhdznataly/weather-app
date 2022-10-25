# weather-app

## task
* Use the 5 Day Weather ForecastLinks to an external site. to retrieve weather data for cities. The base URL should look like the following: https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API key}. After registering for a new API key, you may need to wait up to 2 hours for that API key to activate.

* You will use localStorage to store any persistent data. For more information on how to work with the OpenWeather API, refer to the Full-Stack Blog on how to use API keysLinks.

## user-story 
* AS A traveler
    * I WANT to see the weather outlook for multiple cities
    * SO THAT I can plan a trip accordingly

## acceptance criteria

* GIVEN a weather dashboard with form inputs
    * WHEN I search for a city
        * THEN I am presented with current and future conditions for that city and that city is added to the search history
    * WHEN I view current weather conditions for that city
        * THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the the wind speed
    * WHEN I view future weather conditions for that city
        * THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
    * WHEN I click on a city in the search history
        * THEN I am again presented with current and future conditions for that city

## assets

<img width="600" alt="Screen Shot 2022-10-25 at 6 06 45 PM" src="https://user-images.githubusercontent.com/112514096/197898668-07ccf079-a14b-4b11-b964-77223b71bbc2.png">

