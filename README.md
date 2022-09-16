# Phase 1 Project: Building a Weather Forecasting App
Project Contributors: Chris Dennis, Chris Ding

Our partner group originally came up with the idea to create a weather forecasting application due to the wide array or public weather forecasting APIs available to us, as well as the relatively straightforward nature of building this type of application. As part of our learning curriculum for Flatiron School, we aimed to reinforce several learning concepts such as asynchronous interactions between client and server, event listeners, and array iteration.

## Description
Our Weather App is a single page application, built with Javascript, HTML, and CSS. This application allows the user to search a city globally and see the current weather for that city. This project uses data from https://openweathermap.org/api.

In terms of functionality, our project handles a couple of major weather forecasting events. We have included a side navigation bar that contains several of the most populous U.S. cities and will display the current forecast for said city when clicked upon. We have also included a manual search bar that will forecast the weather for any global city that is typed as an input (assuming correct English translation spelling). 

In either case, the weather forecast for the specific city selected will show the current temperature, the type of weather (e.g. sunny, cloudy, rainy, etc.), what the temperature feels like in actuality, wind speeds, as well as the time of sunrise and sunset (in Pacific Daylight Time GMT-700).

## Project Setup
To prevent access to our public API key, we have chosen to omit the specific key that we used to make server requests from our public weather forecasting API of choice, OpenWeatherMap.org. OpenWeatherMap's API allows any user to register and access their free public weather forecasting API, which is a painless process that only takes a minute. To access our project in full, you would need to create an account and API key at [OpenWeatherAPI]https://home.openweathermap.org/users/sign_up.

Once you have an API key created, copy your generated key and navigate to the index.js file in this project's directory. You will find a variable named ==key== that is assigned to an empty string value of ''. Paste your generated key between these quotation marks and the project will be ready to be run once you open the index.html file in the browser!