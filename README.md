# Weather Update Application

This Weather Update Application is a simple Android app that allows users to fetch and display weather information for a specific location. It utilizes the OpenWeatherMap API to retrieve weather data and provides details such as temperature, humidity, wind speed, and more.

## Features

- Get current weather information for a city.
- Optionally specify the country for more precise results.
- Display temperature in Celsius.
- Show additional weather details, including feels like temperature, humidity, description, wind speed, cloudiness, and pressure.

## Technologies Used

- Android Studio: The application is developed in Android Studio, using Java for programming.

## How to Use

1. Launch the app on your Android device or emulator.

2. Enter the name of the city you want to get weather information for in the "City" field.

3. Optionally, provide the name of the country in the "Country" field to narrow down the search.

4. Tap the "Get Weather" button.

5. The app will make an API request to OpenWeatherMap and display the weather information for the specified location.

## Implementation Details

- The app uses the OpenWeatherMap API to retrieve weather data in JSON format.

- It makes an HTTP request to the API with the city and country information (if provided) and an API key.

- The response JSON is parsed to extract relevant weather information, including temperature, feels like temperature, humidity, description, wind speed, cloudiness, and pressure.

- The retrieved data is then displayed in a user-friendly format on the app's interface.

## Dependencies

- [Volley](https://developer.android.com/training/volley): Volley is used for network requests to fetch data from the OpenWeatherMap API.

## Screenshots

- Include some screenshots of the application in action, showcasing how it looks and the weather information it displays.

## License

This Weather Update Application is open-source and released under the [MIT License](LICENSE). You can use, modify, and distribute the code as per the terms of the license.

## Author

- Ojas Joshi
- ojasnj4@gmail.com

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request to the main repository.

## Issues

If you encounter any issues or have suggestions for improvement, please [open an issue](https://github.com/your-repo/issues) on the project's GitHub repository.

## Support

For any questions or assistance, feel free to contact the author or open an issue on the project's GitHub repository.

---

Enjoy using the Weather Update Application! Stay updated with the latest weather conditions for your favorite cities.
