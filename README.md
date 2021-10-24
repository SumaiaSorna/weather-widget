# Weather-widget

The application provides a number of functionalities: weather data by a selected city, a five-day forecast; a visual representation of data for easy understanding, and a record of several cities that can be searched using this application.

## Description

The work was done using both HTML, CSS and jQuery tools. These tools were applied to develop the weather application that customised data from a third-party API from Open Weather Map. The UV weather parameter was represented by the colour coding from the US EPA website.

## User Story

A traveller can plan a journey based on the weather information as information from multiple cities can be checked. The graphical items and colour coding will help users who find difficulties interpreting numbers. The list of searched cities also will help the users to recall recently searched cities and plan accordingly.

## Deployed link

Click [here](https://sumaiasorna.github.io/weather-widget/) to view the deployed application.

## Technology Used

- HTML5
- CSS3
- Bootstrap
- jQuery
- Javascript
- Moment.js

## Uses of API

Used OpenWeather One Call API to collect weather information.

#### URLs

- First API call used to get city name with lon and lat parameters

```
https://api.openweathermap.org/data/2.5/weather?q=${cityNames}&appid=${API_KEY}

```

- second API call used to get current and forecast weather data

```
https://api.openweathermap.org/data/2.5/onecall?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=imperial

```

## Screenshots

- Desktop Viewport

  ![desktop Viewport](assests\images\screeshots\Weather-Widget-desktop-viewport.png)

- Mobile Viewport

![mobile Viewport](assests\images\screeshots\Weather-Widget-mobile-viewport.png)
