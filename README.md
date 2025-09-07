# 🌦️ Weather App

A responsive and modern Weather App built using **HTML**, **CSS**, and **JavaScript**. It allows users to get real-time weather data based on their **current location** or by **searching for a city**. Weather data is fetched from the **OpenWeatherMap API**.

🚀 [Live Demo](https://weather-app-nine-psi-22.vercel.app/)

---

## 🔥 Features

- 📍 Get weather using **current location** via Geolocation API
- 🔍 Search weather by **city name**
- 🌡️ Shows temperature, humidity, wind speed, and cloudiness
- 🌐 Uses **OpenWeatherMap API**
- 🎨 Clean, modern, and responsive UI
- ⚡ Loading state and error handling
- 📱 Fully responsive on mobile and tablets

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **Geolocation API**
- **OpenWeatherMap API**
- **Vercel** (for deployment)

---

## 📂 Folder Structure

weather-app/
├── index.html
├── styles.css
├── index.js
├── assets/
│ ├── cloud.png
│ ├── location.png
│ ├── search.png
│ ├── humidity.png
│ ├── wind.png
│ └── loading.gif


---

## ⚙️ How It Works

1. On page load, it prompts the user for **location access**.
2. If granted, it fetches weather data for the current coordinates.
3. Alternatively, the user can **search for a city**.
4. Displays weather info: temperature, weather icon, humidity, wind speed, and cloudiness.
5. Uses **`fetch` API** to get data from `https://api.openweathermap.org/data/2.5/weather`.

---

## 📦 API Used

- **OpenWeatherMap API**
  - [https://openweathermap.org/current](https://openweathermap.org/current)

You’ll need your own **API key** (free registration required).

---

## ✅ To Run Locally

```bash
git clone https://github.com/MdZiyaulHaque/Weather-App.git
cd Weather-App
