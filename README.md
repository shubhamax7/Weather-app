# Weather App

A simple, responsive weather app that shows live weather for any city. Built with vanilla HTML, CSS, and JavaScript using the OpenWeatherMap API.

## Features

- **City search** — Enter any city name to get current weather
- **Current conditions** — Temperature (°C), humidity, and wind speed
- **Weather icons** — Visual icons for Clear, Clouds, Rain, Drizzle, and Mist
- **Error handling** — Clear message when a city name is invalid
- **Responsive card UI** — Gradient design that works on different screen sizes

## Tech Stack

- HTML5
- CSS3 (Flexbox, custom properties)
- Vanilla JavaScript (async/await, Fetch API)
- [OpenWeatherMap API](https://openweathermap.org/api)

## Getting Started

### Prerequisites

- A modern web browser
- (Optional) A local server if you run into CORS when opening `index.html` directly — e.g. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code, or `npx serve` in the project folder

### API Key

The app uses OpenWeatherMap’s free API:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api) and get a free API key.
2. In `index.html`, replace the placeholder `apiKey` value with your own key.
3. **Do not commit your API key** if the repo is public. Prefer environment variables or a config file that’s in `.gitignore`.

### Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/YOUR_USERNAME/Weather-app.git
   cd Weather-app
   ```

2. Ensure the `images/` folder exists and contains:
   - `search.png` — search button icon
   - `humidity.png`, `wind.png` — detail icons
   - `clear.png`, `clouds.png`, `rain.png`, `drizzle.png`, `mist.png` — weather icons

3. Open `index.html` in your browser, or run a local server (e.g. `npx serve`) and open the URL shown.

## Project Structure

```
Weather-app/
├── index.html    # Markup and app logic
├── style.css     # Layout and styling
├── images/       # Icons (search, weather, humidity, wind)
└── README.md
```

## License

This project is open source. Use it for learning or as a base for your own weather app.
