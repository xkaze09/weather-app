# 🌤️ Weather App

A dynamic and responsive **Weather Application** built from scratch using **Next.js**, **Tailwind CSS**, and **TypeScript**. This app delivers real-time weather updates with a clean UI and modular React components.

---

## 🚀 Features

- 🔎 **Search Functionality**: Search weather data for any location.
- 📍 **Current Location Support**: Get weather based on your current geolocation.
- 🌤 **Today’s Weather**: Displays temperature, weather conditions, and icons.
- 📅 **7-Day Forecast**: Detailed week-long forecast with condition visuals.
- 🌡️ **Additional Details**: Humidity, wind speed, sunrise/sunset, and more.
- ⚡ **Modern UI**: Designed with Tailwind CSS for a clean and mobile-responsive interface.
- 🔧 **TypeScript Integration**: Strongly-typed for better reliability and developer experience.

---

## 🧩 Component Structure

### 1. **Navbar Component**
- Displays the app title and navigation options.
- Designed for responsive layouts using Tailwind CSS.

### 2. **API & Data Types Configurations**
- External weather API integration.
- Type-safe data modeling using TypeScript interfaces.

### 3. **Current Day Section Components**
- Shows the current temperature, weather description, and location name.
- Includes weather icons and date/time info.

### 4. **Additional Details Component**
- Displays extra metrics such as:
  - Feels-like temperature
  - Wind speed and direction
  - Humidity
  - UV Index

### 5. **7-Day Forecast Section**
- Scrollable card-style layout.
- Daily weather summaries with date, temperature range, and condition icons.

### 6. **Search & Current Location Logic**
- Use of browser geolocation API for instant local weather.
- Debounced input for optimized search requests.

---

## 🛠️ Built With

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [OpenWeatherMap API](https://openweathermap.org/api)

---