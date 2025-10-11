# Weather Dashboard

A modern, responsive weather dashboard built with HTML, CSS, and JavaScript.

## Features

- Real-time weather data from OpenWeather API
- Light and dark mode themes
- Responsive design using Bootstrap
- PWA (Progressive Web App) support
- Search functionality for cities worldwide
- Geolocation support
- Temperature unit conversion (Celsius/Fahrenheit)

## Getting Started

### Prerequisites

1. Get a free API key from [OpenWeather](https://openweathermap.org/api)
2. Sign up for an account and generate your API key

### Setup

1. Clone the repository
2. Open `src/main.js` and replace `'API-KEY-HERE'` with your actual OpenWeather API key:
   ```javascript
   const OPENWEATHER_KEY = 'your-actual-api-key-here';
   ```
3. Open `index.html` in your browser

## Deployment

### GitHub Pages (Recommended)

1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be live at: `https://kartikpatgar15.github.io/Weather-app/`

### Alternative Hosting Options

- **Netlify**: Connect your GitHub repo and deploy instantly
- **Vercel**: Import your repository for automatic deployments
- **Firebase Hosting**: Upload your files for free hosting

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Axios for API calls
- OpenWeather API

## License

MIT License