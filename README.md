# Real-Time Weather App with API Integration 

A simple, real-time weather application that uses **OpenWeatherMap API** to fetch and display live weather updates and forecasts for any city.

## Features

- **Real-time Weather Updates**: Displays current weather conditions such as temperature, humidity, and wind speed for the selected city.
- **City Search**: Allows users to input a city name and view the weather details for that city.
- **Forecast**: Shows the weather forecast for the next few days.
- **Responsive UI**: The app is fully responsive and can be accessed on both desktop and mobile devices.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    cd weather-app
    ```

2. Open the project folder in your favorite code editor.

3. Get your **API Key** from [OpenWeatherMap](https://openweathermap.org/api).

4. Replace the `YOUR_API_KEY` in the `app.js` with your actual API key.

5. Open `index.html` in your browser to see the app in action.

## How it Works

### 1. Front-End Design (HTML, CSS)
The app is designed using **HTML** and **CSS**, with a clean, minimalistic user interface. It displays the weather information, such as temperature, wind speed, and humidity, in a user-friendly format.

### 2. JavaScript and API Integration
- **JavaScript** is used to interact with the **OpenWeatherMap API** and fetch real-time data for the selected city.
- The **fetch()** function is used to make an HTTP request to the API endpoint, get the response, and dynamically display the data on the page.
  
  Example API URL for current weather:
  ```javascript
  https://api.openweathermap.org/data/2.5/weather?q=city_name&appid=YOUR_API_KEY
