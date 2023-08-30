# Weather App

[Weather App Demo]

The Weather App is a simple web application that allows users to check the current weather conditions for a specific location. It utilizes HTML, CSS, and JavaScript to provide a user-friendly interface and real-time weather data fetched from a weather API.

## Features

- **Location Search:** Users can enter the name of a city or location in the search bar and press Enter to get the current weather details.

- **Weather Information:** The app displays essential weather information such as temperature, humidity, wind speed, and weather description.

- **Icon Representation:** Weather conditions are visually represented using weather icons to give users a quick overview.

- **Responsive Design:** The app is designed to be responsive, ensuring a seamless experience on both desktop and mobile devices.

## Technologies Used

- HTML5: Markup structure and content layout.
- CSS3: Styling and layout of the app.
- JavaScript: Interactivity and fetching data from the weather API.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your preferred web browser.

4. Enter the name of the city or location you want to check the weather for in the search bar and press Enter.

5. View the current weather conditions displayed on the screen, including temperature, humidity, wind speed, and weather description.

## API Integration

The Weather App fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api). To use the app, you'll need to sign up for a free API key and replace `'YOUR_API_KEY'` in the `script.js` file with your actual API key.

```javascript
const apiKey = 'YOUR_API_KEY';
const apiUrl = `https://api.openweathermap.org/data/2.5/weather`;
```

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## Contributing

Contributions are welcome! If you find a bug or want to add a new feature, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README according to your project's structure and additional features. Make sure to include any specific setup instructions, deployment guides, or additional details that would help users understand and use your Weather App effectively.
