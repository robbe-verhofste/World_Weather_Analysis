# World_Weather_Analysis

## Concept:

In this project, we created an travel app for location suitability based on user-defined preferences. First, users enter thier optimal temperature range (high and low). Weather data is then pulled from OpenWeatherAPI and combined with CitiPy via lat-long coordinates. This provides a list of cities with a suitable temperature range for the user. On January 17th, 2021, for example, there were 333 cities with a temperature range of 60-100F.

Next, these cities are linked with the Google Places API. This API finds nearby hotels in each city with suitable temperatures. Lastly, an itinerary is created by a user-defined selection of 4 optimal places, via Google Directions API.
