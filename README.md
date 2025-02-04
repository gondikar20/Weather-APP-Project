# Weather App 🌤️

A simple and elegant weather application that allows users to check the current weather conditions for any location. The app fetches weather data using the WeatherAPI.

## Features
- Enter a location to get the current temperature and weather condition.
- Stylish design with a weather-themed background image.
- User-friendly and responsive interface.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling, including a beautiful background image.
- **JavaScript**: Fetching weather data from the WeatherAPI and dynamically updating the UI.
- **WeatherAPI**: Provides accurate and up-to-date weather data.

## How to Use
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Open the `index.html` file in any web browser.
3. Enter a location in the input field and click the "Get Weather" button.
4. The current temperature and weather condition will be displayed.

## API Key
This application uses the WeatherAPI. Replace the `key` parameter in the `apiUrl` variable in the JavaScript file with your API key if required.

Example:
```javascript
const apiUrl = `http://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${location}&aqi=yes`;
```


