# Weather-API-application HTML CSS JS

A web application built with HTML, CSS, and JavaScript that fetches and displays real-time weather information from a public Weather API.

## Overview

This project provides users with a simple and intuitive way to get current weather details for any location worldwide. By leveraging a public Weather API, the application dynamically retrieves data such as temperature, humidity, wind speed, and weather conditions, presenting it in an easy-to-understand format within the browser. It's a client-side application, making use of asynchronous requests to fetch and display data without requiring a server-side backend.

## Features

- **Location-Based Search:** Allows users to input a city name to retrieve weather information for that specific location.
- **Real-time Weather Data:** Fetches up-to-date weather information from a reliable Weather API.
- **Real-time Weather Forecast Data:** Displaying weather forecasts for the next few days.
- **Key Weather Indicators:** Displays essential weather details including:
  - Current Temperature (in Celsius and/or Fahrenheit)
  - Weather Condition (e.g., Sunny, Cloudy, Rainy) with corresponding icons.
  - Humidity level.
  - Wind Speed.
- **Clean and Responsive Design:** Utilizes CSS to provide a visually appealing and adaptable layout across different screen sizes.
- **Client-Side Logic:** Implemented entirely with JavaScript to handle user input, API calls, data processing, and dynamic updates to the HTML.

## Technologies Used

- **HTML:** Provides the structural foundation for the application's user interface.
- **CSS:** Styles the appearance of the application, ensuring a user-friendly and visually engaging experience.
- **JavaScript:** Handles the core functionality, including:
  - Capturing user input.
  - Making asynchronous API requests to fetch weather data.
  - Parsing the JSON response from the API.
  - Dynamically updating the HTML content to display the weather information.

## How to Use

1.  Clone or download this repository.
2.  Obtain an API key from a public Weather API provider (e.g., OpenWeatherMap, WeatherAPI.com).
3.  Open the `index.html` file in your web browser.
4.  Enter the name of a city in the search bar.
5.  Click the "Search" or a similar button to retrieve the weather information for the specified location.
6.  The application will then display the current weather details.

**Note:** You will need to integrate your API key into the JavaScript code to successfully fetch data from the Weather API. Look for a section in the JavaScript file where the API key needs to be inserted.

## Potential Future Enhancements

- Adding options to change temperature units (Celsius/Fahrenheit).
- Implementing geolocation to automatically detect the user's current location.
- Improving the visual design and adding more detailed weather information (e.g., pressure, visibility).
- Adding error handling for API request failures or invalid input.
