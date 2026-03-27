# SheCodes Weather App 🌤️

A responsive weather app inspired by [weather.shecodes.io](https://www.weather.shecodes.io/), built with vanilla HTML, CSS and JavaScript.

## Features
- Search weather by city name
- Detect location automatically (📍 My Location)
- Switch between °C and °F
- 6-day forecast strip
- Responsive design (mobile-friendly)

## Setup

### 1. Get an OpenWeatherMap API key
1. Go to [openweathermap.org](https://openweathermap.org/api) and create a free account
2. Copy your API key from the dashboard

### 2. Add your API key
In `index.html`, replace:
```js
const API_KEY = 'YOUR_OPENWEATHERMAP_API_KEY';
```
with your actual key.

### 3. Deploy to Netlify
1. Push this folder to a GitHub repository
2. Log in to [netlify.com](https://netlify.com)
3. Click **Add new site → Import an existing project**
4. Connect your GitHub repo
5. Leave the build settings blank (static site)
6. Click **Deploy site**
7. Your live URL will appear on the dashboard (e.g. `https://your-app.netlify.app`)

### 4. Add GitHub link to footer
In `index.html` update the footer link:
```html
<a href="https://github.com/YOUR-USERNAME/shecodes-weather" ...>
```

## Tech stack
- HTML5 · CSS3 (glassmorphism, CSS Grid, Flexbox)
- Vanilla JavaScript (Fetch API)
- [OpenWeatherMap API](https://openweathermap.org/api) (current weather + 5-day forecast)
- Google Fonts — Nunito
