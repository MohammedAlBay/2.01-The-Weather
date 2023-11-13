# The Weather Application

- Repository: `weather-app`
- Type of Challenge: `Learning`
- Duration: `5 days`
- Deployment strategy: `Github pages / Netlify`
- Team challenge : `solo`

## Mission objectives

In this challenge you will use and consolidate your knowledge on:

- A typical AJAX flow: send asynchronous requests to a remote server and process the results
- DOM manipulation: changing the DOM based on the results of the AJAX-like requests
- Learn to aggregate and parse data fetched from an API

## The Mission

You have been sent abroad for a 10-month work mission. Your family and friends back home ask you about the weather where you live ALL. THE. TIME.  
Enough is enough, you decide to build a small web application for them so that you can free your time to talk about more interesting topics.

### 🌱 Must haves

- In the home page the user can enter the city of his/her choice (think of the right HTML elements here)
- On clicking the SUBMIT button or pressing ENTER:
    - Use an api to define the city geo-location data from the user-input
    - Use an api to get the weather data for at least the next 5 days
    - Manipulate your DOM in order to display the weather for the next 5 days in your application.
- Find a way to make those API calls asynchronous.
- The application must be responsive, accessible and mobile friendly

> 💡 Not sure where to start? Split this features into multiple smaller todos (in your code, sketch, ...)

### 🌼 Nice to haves (in no specific order)

- Display a line graph of temperature over time using a library such as [Chart.js](https://www.chartjs.org)
- Remember the user choice on subsequent visits
- Allow the user to compare the weather in two cities
- Use the API of https://unsplash.com/ to show a photo of the city they entered in the form

### Resources

- Get the geo-location from the city with an API ([Open-Meteo geo-location](https://open-meteo.com/en/docs/geocoding-api) has the option to do so, but feel free to use other api's)
- Then use the geo-coordinates to get the weather data from the [Open-Meteo Weather API](https://open-meteo.com/en/docs) by using the native JS [`fetch()`](https://devdocs.io/dom/fetch_api/using_fetch) method (if you like, you can also check out [axios](https://github.com/axios/axios))