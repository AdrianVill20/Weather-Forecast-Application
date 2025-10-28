## Weather Forecast Application
## Concept:
A web app that retrieves live weather data from a public API (e.g., Open-Meteo or WeatherAPI.com)
using XMLHttpRequest wrapped in a Promise.

## Core Learning Goals:
 Using Promises to handle HTTP responses and errors.<br>
 Chaining Promises for sequential operations (e.g., first get coordinates → then get forecast).<br>
 Updating UI dynamically with resolved Promise data.<br>

## Example Flow:
1. User enters a city name.
2. getCoordinates(city) returns a Promise (uses XHR).
3. When resolved, it passes latitude/longitude to getWeather(lat, lon) (also returns a Promise).
4. The data is displayed in the browser (temperature, humidity, condition icon).
