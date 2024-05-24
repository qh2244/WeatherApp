# WeatherApp
# Weather App

A simple weather application that fetches and displays weather information for a specified city using the OpenWeatherMap API.

## Features

- Search for weather information by city name.
- Displays current temperature, humidity, and wind speed.
- Shows appropriate weather icon based on weather conditions.
- Error handling for invalid city names.
- User-friendly interface.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-app
    ```

3. Open `index.html` in your preferred web browser.

### Usage

1. Enter the name of a city in the search box.
2. Click the search button or press Enter.
3. View the current weather information for the specified city.

## API Key

This application uses the OpenWeatherMap API to fetch weather data. You need an API key to use this app. Follow these steps to obtain and configure the API key:

1. Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Go to the API Keys section and generate a new API key.
3. Replace the `apiKey` variable value in the `index.html` file with your API key:

    ```javascript
    const apiKey = "your_api_key_here";
    ```

## Project Structure

