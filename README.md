# Weather App

A simple Flutter app that displays current weather and a short hourly forecast for a given location. The app uses the OpenWeatherMap API to fetch real-time weather data.

## Features

- **Real-Time Data:**  
  Fetches live weather data using the OpenWeatherMap API.
  
- **Current Weather:**  
  Displays the current temperature (converted from Kelvin to Celsius), a weather icon, and a brief weather description.
  
- **Hourly Forecast:**  
  Shows a horizontal list of the forecast for the next few hours, including the time and temperature.
  
- **Additional Information:**  
  Provides extra details such as humidity, wind speed, and atmospheric pressure.
  
- **Refreshing Data:**  
  Supports pull-to-refresh and a refresh button in the AppBar to update weather information manually.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev) installed on your machine.
- An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/weather_app.git
   cd weather_app
Install Dependencies:

Run the following command to get all required packages:


flutter pub get
Configure the API Key:

Open the secrets.dart file and replace the placeholder with your OpenWeatherMap API key:

dart

const String openWeatherAPIkey = 'YOUR_API_KEY_HERE';
Run the App:

Use the following command to launch the app on an emulator or connected device:


flutter run
Project Structure
WeatherScreen
The main screen of the app which handles fetching data, displaying the current weather, the hourly forecast, and additional weather details.

Networking:
Utilizes the http package to make asynchronous API calls.

UI Components:
Custom widgets like HourlyForecastItem and AdditionalInfoItem are used to modularize the interface.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
OpenWeatherMap API for providing real-time weather data.



