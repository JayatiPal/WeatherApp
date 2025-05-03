# Aesthetic Weather App

## Overview
A simple web/mobile app that shows the current weather and forecasts using OpenWeatherMap data, paired with smooth Lottie animations for an engaging look.

## Features
- **Current Conditions**: Temperature, description, humidity.
- **Hourly & Daily Forecasts**: Up to 48 hours and 8 days.
- **Lottie Animations**: Contextual animations (sunny, rainy, snowy).
- **Light/Dark Mode**: Switch themes to match your preference.

## Installation
1. **Clone Repository**  
   `git clone https://github.com/yourusername/aesthetic-weather-app.git`  
   `cd aesthetic-weather-app`

2. **Install Dependencies**  
   `npm install`

3. **Set Up API Key**  
   - Get an API key from https://openweathermap.org/  
   - Create a `.env` file in project root:  
     ```
     REACT_APP_OWM_API_KEY=your_api_key_here
     ```

4. **Run Locally**  
   `npm start`

## Usage
Import and use the `WeatherWidget` component with your coordinates:

```jsx
<WeatherWidget lat={12.34} lon={56.78} />
```

## Adding Lottie Animations
1. Download `.json` files from https://lottiefiles.com/  
2. Install: `npm install react-lottie`  
3. Map weather conditions to your Lottie JSON in your code.

## Contributing
1. Fork -> Branch -> Commit -> Push -> PR  
2. Follow code style and add tests if needed.


