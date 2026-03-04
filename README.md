Weather-app
 Weather App 

A responsive weather application built using **React.js and Vite** that displays real-time weather information for any city using the **OpenWeather API**.

Features

* Search weather by city name
* Displays current temperature in Celsius
* Shows humidity and wind speed
* Dynamic weather icons based on weather conditions
* Clean and responsive user interface

 Technologies Used

* React.js
* JavaScript (ES6)
* HTML5 & CSS3
* Vite
* OpenWeather API

How It Works

The application fetches real-time weather data from the OpenWeather API based on the city entered by the user. It then displays the weather details including temperature, humidity, wind speed, and corresponding weather icons dynamically using React state management.

Getting Started

1. Clone the repository
git clone https://github.com/yourusername/weather-app.git

2. Install dependencies
npm install

3. Run the project
npm run dev

Project Structure

```
weather-app
│
├── src
│   ├── assets
│   ├── components
│   │   └── Weather.jsx
│   ├── App.jsx
│
├── public
├── package.json
├── vite.config.js
```

 Future Improvements

* Add 5-day weather forecast
* Implement geolocation to fetch weather based on current location
* Improve UI with animations and loading indicators
