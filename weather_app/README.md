# Weather App

## Overview

The Weather App is a simple Flutter application that allows users to check the weather forecast for a specific city. It provides information about the current weather conditions, hourly forecasts, and additional weather details.

## Features

- **Current Weather:** Display the current temperature, sky conditions, and an icon representing the weather.

- **Hourly Forecast:** Show a forecast for the next five hours, including the time, temperature, and weather icon.

- **Additional Information:** Provide additional weather details such as humidity, wind speed, and pressure.

- **Refresh Data:** Allow users to refresh weather data by tapping the refresh button on the app bar.

## Getting Started

To run the Weather App on your local machine, follow these steps:

1. Clone this repository to your computer:

   ```
   git clone https://github.com/hammadali1805/weather_app_flutter.git
   ```

2. Navigate to the project directory:

   ```
   cd weather_app_flutter
   ```

3. Install dependencies:

   ```
   flutter pub get
   ```

4. Obtain an OpenWeatherMap API Key:

   - Visit [OpenWeatherMap](https://openweathermap.org/) and create an account if you don't have one.
   - Generate an API key.
   - Replace the value of const `openWeatherAPIKey` in `secrets.dart` with your actual API key.

5. Run the app:

   ```
   flutter run
   ```

## Usage

- When you launch the app, it will display weather information for the city provided.
- You can refresh the weather data by tapping the refresh button on the app bar.
- The hourly forecast section shows the weather forecast for the next five hours.

## Dependencies

The Weather App uses the following packages:

- `http`: For making HTTP requests to fetch weather data.
- `intl`: For formatting dates and times.
- `flutter/material.dart`: For building the app's user interface.

You can find these dependencies in the `pubspec.yaml` file and install them using `flutter pub get`.

## Contribution

Contributions to the Weather App are welcome! You can contribute by:

- Reporting issues or suggesting enhancements.
- Submitting pull requests to address existing issues.
- Adding new features or improvements.
- 
## Acknowledgments

- Weather data is provided by [OpenWeatherMap](https://openweathermap.org/).

## Contact

If you have any questions or need further assistance, feel free to contact us at [hammadalipbt18@gmail.com](mailto:hammadalipbt18@gmail.com).

---

Enjoy checking the weather with the Weather App!
