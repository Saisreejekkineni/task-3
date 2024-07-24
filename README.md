# task-3
NAME : J SAI SREE
INTERN ID : SMI72615
DOMAIN : FULL STACK WED DEVELOPMENT
DURATION : JUN 1- AUG 1

Overview of the Weather Forecast Website
Objective
Develop a web application that allows users to view the current weather and a five-day forecast for any location. The app will use a weather API to fetch real-time weather data and display it to users. Additionally, it will feature automatic location detection.

Skills Required
JavaScript
Node.js
ReactJS
Key Features
Location Input:
Users can enter a location (city, coordinates) to get weather information.
Optionally, users can select a location from a suggestion list.
Automatic Location Detection:
Uses the browser’s Geolocation API to detect the user's current location.
Fetches and displays weather data based on the detected location.
Weather Forecast Display:
Shows the current weather and a detailed five-day forecast.
Includes temperature, weather conditions (e.g., sunny, rainy), humidity, and wind speed.
Responsive Design:
The application is designed to be mobile-friendly and accessible on various devices.
Technical Breakdown
1. Backend (Node.js)
Server Setup:
A Node.js server using Express to handle API requests.
Endpoint /api/weather that takes a location as a query parameter and fetches weather data from the weather API.
API Integration:
Uses axios to make HTTP requests to the weather API (e.g., WeatherAPI).
Processes and formats the response data to send to the frontend.
Error Handling:
Includes basic error handling for invalid requests and issues with fetching data.
