# weather_repo

Here I have fetched weather data from the OpenWeatherMap API based on a user-entered city. It dynamically updates the UI with the weather information, including temperature, humidity, and wind speed. Different weather conditions are depicted by corresponding icons. If the city is not found or the API request fails, an error message is displayed. There is an event listener to a search button, triggering the weather check function when clicked, using the value entered in the search input field.

 If the requested city is not found, the error message is displayed prominently to the user while hiding the weather information. This ensures a clear and intuitive user experience. Moreover, by leveraging asynchronous JavaScript (async/await), the code efficiently manages API calls without blocking the browser's main thread, enhancing responsiveness. Overall, it's a concise and well-structured implementation for a weather information application.

TECH STACK USED :- 
1. OpenWeatherMap API -I have used this for fetching the real time data of the weather.
2. Tools - Html, JavaScript, CSS, Bootstrap.
