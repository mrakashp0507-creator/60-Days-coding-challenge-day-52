# 🌦️ Weather Intelligence Client

A Python application that fetches live weather information
for multiple cities using the Open-Meteo public API.

## Features

- Fetch live weather data for multiple cities.
- Convert city names into geographic coordinates.
- Parse JSON API responses.
- Display temperature, feels-like temperature,
  humidity, wind speed and weather conditions.
- Handle invalid city names and API failures.
- Display local time for each city.

## Technologies Used

- Python
- REST API
- JSON
- Requests library
- Open-Meteo Weather API
- Open-Meteo Geocoding API

## Project Structure

weather-intelligence/
- main.py
- weather_service.py
- requirements.txt
- README.md

## Installation

1. Clone the repository:

   git clone YOUR_GITHUB_REPOSITORY_URL

2. Open the project folder:

   cd weather-intelligence

3. Install dependencies:

   pip install -r requirements.txt

4. Run the application:

   python main.py

## API Integration

This project uses two APIs:

1. Geocoding API:
   Converts city names into latitude and longitude.

2. Weather Forecast API:
   Fetches current weather information using coordinates.

Both APIs return JSON data.

## Error Handling

The application handles:

- Invalid city names.
- Network connection failures.
- HTTP errors.
- Invalid JSON responses.
- Missing weather information.

## Learning Outcomes

- Understanding REST API communication.
- Sending HTTP GET requests.
- Parsing JSON responses.
- Handling API exceptions.
- Separating application logic into modules.

## Future Improvements

- Add a graphical dashboard using Streamlit.
- Add 7-day weather forecasts.
- Add weather comparison charts.
- Store historical weather information.
- Add air quality information.

## Data Source

Weather data provided by Open-Meteo.
https://open-meteo.com/

Weather API data is available under the CC BY 4.0 licence.
Please provide appropriate attribution.
