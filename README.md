Overview:

The Weather App is a web application that allows users to get real-time weather information for any city.

The application fetches data from a weather API and displays the current weather conditions, including temperature, humidity, wind speed, and more.

Features:

Real-time weather updates Search weather by city name Responsive design for mobile and desktop Easy-to-use interface

Technologies Used:
HTML CSS Node.js Express.js

Installation Clone the repository:

git clone https://github.com/your-username/weather-app.git

Navigate to the project directory: cd weather-app

Install the dependencies: npm install 

Start the server: npm start

Open your browser and go to: http://localhost:3000

Enter the name of a city in the search bar to get the weather information.

Configuration

To use this app, you need to configure your API key for the weather service. Follow these steps:

Sign up for an API key at OpenWeatherMap.

Create a .env file in the root of the project directory and add your API key:

WEATHER_API_KEY=your_api_key_here

Project Structure weather-app/ │ ├── public/ │ ├── css/ │ │ └── styles.css │ └── js/ │ └── scripts.js │ ├── views/ │ ├── index.ejs │ └── layout.ejs │ ├── .env ├── app.js ├── package.json └── README.md

