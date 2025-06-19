PRODIGY-INFOTECH-Tasks
Weather ,Portfolio,StopWatch,GobalFInace,Tic-tac-Toe
Weather App in React - GitHub README

 Project Overview

This is a weather application built with React that provides real-time weather updates for locations worldwide. The app features a clean, responsive interface and utilizes a weather API to fetch current conditions and forecasts.

Features

- **Current Weather Display**: Shows temperature, humidity, wind speed, and weather conditions
- **Location Search**: Search for weather by city name
- **Responsive Design**: Works on mobile, tablet, and desktop devices
- **Weather Icons**: Visual representation of current weather conditions
- **Forecast Data**: 5-day weather forecast
- **Unit Toggle**: Switch between Celsius and Fahrenheit

 Technologies Used

- React.js
- Axios (for API calls)
- OpenWeatherMap API
- CSS Modules (for styling)
- React Icons
- React Loading Skeleton (for loading states)

 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app-react.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app-react
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

5. Start the development server:
   ```bash
   npm start
   ```

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App configuration

## Project Structure

```
weather-app-react/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── CurrentWeather.js
│   │   ├── Forecast.js
│   │   ├── SearchBar.js
│   │   └── WeatherCard.js
│   ├── App.js
│   ├── index.js
│   ├── styles/
│   │   ├── App.module.css
│   │   └── ...
│   └── utils/
│       └── api.js
├── .gitignore
├── package.json
└── README.md
```

 API Usage

This project uses the OpenWeatherMap API. You'll need to sign up for a free API key at [https://openweathermap.org/api](https://openweathermap.org/api).

 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


 Contact

For questions or feedback, please contact:
- Gouse Velluri
- Email: gousevelluri2004@gmail.com
- GitHub:Gouse-1234
