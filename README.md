# 🌦️ Java Weather App

This is a simple Java Weather App that uses the OpenWeatherMap API to fetch real-time weather data for any city.

## 🚀 Features

- Get weather by city name
- Displays temperature (°C), humidity, and weather description
- Uses REST API and JSON parsing

## 🧰 Tech Stack

- Java Core
- `HttpURLConnection` for HTTP GET requests
- `org.json` for JSON parsing
- Console I/O (JavaFX version coming soon!)

## ⚙️ How to Run

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Clone this repo
3. Add the `org.json` library to your classpath
4. Replace `YOUR_API_KEY` in `WeatherService.java`
5. Compile & run:
   ```bash
   javac -cp ".;lib/json-20210307.jar" src/*.java
   java -cp ".;lib/json-20210307.jar;src" Main
