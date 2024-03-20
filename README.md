--->  CodTech IT Solutions Internship   <---

-->   WeatherForcastApp_COD4420   <---
//  WEB DEVELOPMENT TASK TWO
WEATHER FORECAST APP      //

--->  Intern details  <---
Name : Shaik Asma
ID : COD4420

    ----> CODE EXPLAINATION <----
---> HTML:
- The HTML code sets up the structure of the webpage.
- It includes input fields for users to enter a location, a search button, elements to display weather information (temperature, city name, humidity, wind speed), and an error message container.
- The structure is divided into several `div` elements with specific classes for styling and JavaScript manipulation.

 --->  CSS:
- The CSS code provides styling for different elements in the HTML.
- It defines the layout, colors, sizes, and spacing of various components.
- It uses flexbox and other layout techniques for positioning elements within the container.
- Background images and gradients are used to style the background of the webpage.

---> JavaScript:
- JavaScript code handles the functionality of fetching weather data from the OpenWeatherMap API and updating the UI accordingly.
- It defines constants for the API key, API URL, and DOM elements.
- An asynchronous function `checkWeather(city)` is defined to fetch weather data based on the user's input.
- Inside the `checkWeather` function, a `fetch` request is made to the OpenWeatherMap API using the provided API key and city name.
- If the API request is successful (status code 200), the weather data is retrieved in JSON format.
- The weather data is then used to update the UI elements such as city name, temperature, humidity, wind speed, and weather icon.
- Different weather conditions are handled by changing the source of the weather icon image based on the `data.weather[0].main` property.
- If the API request fails (status code 404), indicating an invalid city name, an error message is displayed, and the weather display is hidden.
- An event listener is added to the search button, which triggers the `checkWeather` function when clicked, passing the value of the input field as the city name parameter.

Overall, the code combines HTML, CSS, and JavaScript to create a simple weather forecasting application that allows users to enter a location and view its current weather conditions.
