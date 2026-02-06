# 🌦️ Weather App

A simple and responsive weather application built using **HTML, CSS, and JavaScript**.  
The app fetches real-time weather data from the **OpenWeather API** and displays current temperature, humidity, weather conditions, and an appropriate weather icon for any searched city.

---

## 🚀 Features

- Search weather by city name
- Displays:
  - Temperature (°C)
  - Humidity
  - Weather description
  - Weather emoji based on conditions
- Error handling for invalid city names
- Clean and minimal UI
- Beginner-friendly project structure

---

## 🛠️ Tech Stack

- **HTML** – Structure
- **CSS** – Styling
- **JavaScript (ES6)** – Logic & API handling
- **OpenWeather API** – Weather data

---

## 📂 Project Structure

```js
weather-app/
│
├── index.html
├── script.js
├── style.css
└── README.md

```
---

## 🔑 API Key Setup 

This project uses the **OpenWeather API**.  
<!-- For security reasons, the API key is **not included** in the repository. -->

### Follow these steps to run the project locally:

1. Go to https://openweathermap.org/api  
2. Create a free account and generate an API key  
3. In the project root folder, create a file named `config.js`
4. Add the following code:

```js
export const API_KEY = "YOUR_OPENWEATHER_API_KEY";
```
5. Open index.html in your browser

### ⚠️ Note on API Security

Since this is a frontend-only project, API keys cannot be fully hidden in production.
For real-world applications, API requests should be handled via a backend or environment variables using build tools.

### 📸 Preview
<p align="center">
    <img src="assets/image1.png" alt="UI Preview" width="400" height="200"/>
    <img src="assets/iamge2.png" alt="UI Preview" width="400" height="200"/>
</p>

### 🙌 Acknowledgements
- OpenWeather API – https://openweathermap.org/
