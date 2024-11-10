<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weather App README</title>
</head>
<body>
  <h1>Weather App</h1>
  <p>This weather app provides current weather information for a specified city. The app displays temperature, humidity, wind speed, and other details with a user-friendly interface.</p>

  <h2>App Screenshot</h2>
  <img src="Images/Screenshot.png" alt="Weather App Screenshot" width="500">

  <h2>Features</h2>
  <ul>
    <li>Search weather by city name</li>
    <li>Display current temperature, humidity, and wind speed</li>
    <li>Shows weather icons based on conditions (e.g., rain, clear, clouds)</li>
    <li>Responsive and intuitive design</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>HTML, CSS, JavaScript</strong> - for frontend development</li>
    <li><strong>OpenWeatherMap API</strong> - for fetching weather data</li>
  </ul>

  <h2>Getting Started</h2>
  <h3>Prerequisites</h3>
  <ul>
    <li>API Key from <a href="https://openweathermap.org/" target="_blank">OpenWeatherMap</a></li>
  </ul>

  <h3>Installation</h3>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/your-username/weather-app.git
cd weather-app</code></pre>
    </li>
    <li>Replace `apiKey` in the HTML file with your actual API key.</li>
    <li>Ensure images (like `clear.png`, `rain.png`, etc.) are in the `images` folder.</li>
  </ol>

  <h2>Usage</h2>
  <ol>
    <li>Open the `index.html` file in a browser.</li>
    <li>Enter the city name in the search box and click the search button.</li>
    <li>Weather information for the city will display below.</li>
  </ol>

  <h2>Code Explanation</h2>
  <p>The app fetches data from the OpenWeatherMap API. When the user enters a city name and clicks search, the `checkWeather()` function is called to get the weather data and update the display with the current temperature, humidity, wind speed, and weather icon.</p>

  <h2>Contributing</h2>
  <p>Feel free to submit issues or create pull requests to improve the project. Contributions are welcome!</p>

  <h2>License</h2>
  <p>This project is licensed under the MIT License.</p>
</body>
</html>
