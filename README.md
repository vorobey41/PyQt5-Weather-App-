PyQt5 Weather App 🌦️

A sleek and interactive weather application built with Python and PyQt5, fetching real-time weather data from the OpenWeather API. This app is perfect for users who want a quick overview of the current weather conditions in any city worldwide.

### 🌟 Features

- **City Search** 🔍: Enter any city name to get the latest weather information.
- **Real-Time Weather Data** 📊: Displays up-to-date temperature, weather condition, and an emoji icon representing the current weather.
- **Error Handling** ⚠️: Provides user-friendly error messages for common issues, such as incorrect city names, API errors, or network issues.

### 📋 How It Works

1. **Input the City** 🌆: Type the name of the city you want to check the weather for.
2. **Get the Weather** 🌍: Click the "Get Weather" button to fetch the latest weather data.
3. **View Results** 👀: See the current temperature in Celsius, weather description, and a representative emoji (e.g., ☀️ for sunny, 🌧️ for rain, ❄️ for snow).

### 🖥️ User Interface

The UI is designed to be simple and intuitive:
- **Centered Input** 🖋️: The city name input is centrally aligned for easy access.
- **Large Text** 📏: The temperature and weather description are displayed in large, readable fonts.
- **Weather Emoji** 🌈: Each weather condition is accompanied by an emoji, making it visually engaging.

### 💻 Code Highlights

- **API Integration** 🌐: Utilizes the OpenWeather API to fetch weather data based on user input.
- **Error Handling** ❗: Built-in error handling for invalid city names, API key issues, and network errors.
- **Dynamic Emoji Display** 😎: The app uses emojis to represent weather conditions based on the OpenWeather data.

### 🌍 Weather Condition Emojis

The app dynamically displays an emoji based on the current weather condition:
- **Clear Sky** ☀️
- **Few Clouds** 🌤️
- **Scattered Clouds** ☁️
- **Rain** 🌧️
- **Thunderstorm** ⛈️
- **Snow** ❄️
- **Fog** 🌫️

### 🛠️ Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/WeatherApp.git
   cd WeatherApp
