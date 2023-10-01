# Weather App

This is a simple weather application that allows users to check the weather conditions for a specific city. Users can enter the city name in the search bar, press "Enter," and get real-time weather information.

## Features

- **City Search:** Enter the name of the city you want to check the weather for.
- **Real-time Data:** Get real-time weather data, including temperature, humidity, wind speed, and weather situation (e.g., Rain, Clouds, Haze).
- **Weather Icons:** The app displays weather icons based on the current weather situation.
- **Responsive Design:** The application is designed to work seamlessly across various devices and screen sizes.

## How to Use

1. **Clone the Repository:**
   ```
   git clone <repository-url>
   cd weather-app
   ```

2. **Open the HTML File:**
   - Open the `index.html` file in your web browser.

3. **Enter City Name:**
   - In the search bar, enter the name of the city you want to check the weather for.
   - Press "Enter" to view the weather details for the specified city.

## API Key

This application uses the OpenWeatherMap API to fetch weather data. You need to obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder `apiKey` in the `script.js` file with your actual API key.

```javascript
const apiKey = "YOUR_API_KEY";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
```

## Technologies Used

- HTML
- CSS
- JavaScript


## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize and use this weather app for your own purposes! If you encounter any issues or have suggestions for improvements, please feel free to contribute or open an issue.