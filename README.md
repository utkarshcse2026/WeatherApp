# Weather App🌥️

## Overview

This Weather App is a simple web application that allows users to check the current weather conditions for a specific location. The app utilizes a weather API to fetch real-time weather data and displays it in a user-friendly interface.

## Features

- **Current Weather:** Get up-to-date information about the current weather in any location.
- **Temperature:** Display the current temperature in Celsius or Fahrenheit.
- **Humidity and Wind Speed:** View additional details such as humidity and wind speed.
- **User-friendly Interface:** Intuitive design for a seamless user experience.

## Demo : https://www.loom.com/share/bd46cdcc03a34cc1b72493f6487ed612

## Installation

Follow these steps to set up and run the Weather App on your local machine:

### Prerequisites

1. **Node.js:** Ensure that Node.js is installed on your machine. You can download it from [https://nodejs.org/](https://nodejs.org/).

2. **API Key:** Obtain a free API key from a weather API provider. This app uses the OpenWeatherMap API, and you can get a key by signing up at [https://openweathermap.org/api](https://openweathermap.org/api).

### Setup

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-app
    ```

3. Install the project dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the project root and add your OpenWeatherMap API key:

    ```env
    REACT_APP_API_KEY=your-api-key
    ```

### Run the App

Once you have completed the setup, start the development server:

```bash
npm start
```

The app will be accessible at [http://localhost:3000](http://localhost:3000) in your web browser.

## Configuration

You can customize the app's behavior by modifying the following configuration options in the `.env` file:

- **REACT_APP_API_KEY:** Your OpenWeatherMap API key.
- (Optional) **REACT_APP_UNITS:** The unit system for temperature. Set to `metric` for Celsius or `imperial` for Fahrenheit.

## Contributing

If you would like to contribute to the development of this Weather App, please follow the guidelines in CONTRIBUTING.md.❤️

## License

This Weather App is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to update this README file with any additional information or specific details related to your project.🙌
