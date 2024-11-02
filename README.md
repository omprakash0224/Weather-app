## Weather App🌤️

This is a simple weather application built using HTML, CSS, and JavaScript. The app fetches real-time weather information for any location using the [OpenWeatherMap API](https://openweathermap.org).

## Features

+ **Location Search:** Enter a city or location to get the latest weather information.
+ **Real-time Weather Data:** Fetches data including:
  + **Temperature** 🌡️
  + **Humidity** 💧
  + **Wind Speed** 🌬️

## Demo

**Getting Started**

**Prerequisites**

+ An OpenWeatherMap account and API key to access weather data.

**Installation**

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```
2. Open `index.html` in your browser.

## Usage

  1. Enter a location name in the search bar.
  2. Press Search to get the weather information.

## Code Highlights

+ **HTML:** Structure of the application
+ **CSS:** Styling for a clean and responsive interface
+ **JavaScript:** Fetches weather data from OpenWeatherMap and updates the UI

## API Integration

+ The app uses **OpenWeatherMap** to fetch weather data. Ensure you add your OpenWeatherMap API key to the `script.js` file for API requests.

```bash
fetch(`https://api.openweathermap.org/data/2.5/weather?q=${location}&appid=YOUR_API_KEY`)
```
