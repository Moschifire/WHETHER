# WHETHER

Whether is a weather application that takes in the name of a city and provides weather information regarding the city.
The application is created with react. Other components of the application of react-accordion and AsyncPaginate.
I decided to build a weather application because other weather applications did not show weather forecast for my area. They display weather information for neighbouring areas but do not display for my area. It was during the course of building this app thag I realized that my city wasn't displayed on weather applications because the cities/location APIs didn't find my area probably because of the population or for some other reasons still unknown to me.
The deployed website is available at [https://whether-eta.vercel.app/]

## Search

The search component takes in data and provides information from an API [https://wft-geo-db.p.rapidapi.com/v1/geo]. The application provides information for cities with a population of at least 100000.

## Current weather

The current weather widget renders the current weather situation of the searched city, rendering information from [https://api.openweathermap.org/data/2.5/].

## Forecast

The forecast widget makes use of react accordion to render daily weather forecast over a weeks duration.

## Moving forward

Moving forward, I have intentions of making the application more advanced by adding weather updates by the hour.
