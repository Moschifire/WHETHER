# WHETHER

Whether is a weather application that takes in the name of a city and provides weather information regarding the city.
The application is created with react. Other components of the application of react-accordion and AsyncPaginate.

## Search

The search component takes in data and provides information from an API [https://wft-geo-db.p.rapidapi.com/v1/geo]. The application provides information for cities with a population of at least 100000.

## Current weather

The current weather widget renders the current weather situation of the searched city, rendering information from [https://api.openweathermap.org/data/2.5/].

## Forecast

The forecast widget makes use of react accordion to render daily weather forecast over a weeks duration.