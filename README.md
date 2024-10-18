
# 🌤️ Weather Dashboard - React + Vite

This project is a **Weather Dashboard** application that allows users to search for cities and view current weather information along with a 7-day forecast. It's built using **React** with **Vite** for fast development, and it fetches weather data from **OpenWeatherMap** API. ⛅

## 📸 Screenshots (Add your images here)

### Home Screen 🌍


### Search City 🔎
![Search City Placeholder](https://via.placeholder.com/800x400)

### 7-Day Forecast 📅
![7-Day Forecast Placeholder](https://via.placeholder.com/800x400)

---

## ⚙️ Installation Instructions

### 1. Clone the Repository 🛠️

To get a local copy of the project, clone the repository by running the following command:

```bash
git clone https://github.com/Khaleeq01/React-Weather-App.git
cd React-Weather-App
```

### 2. Install Dependencies 📦

Navigate to the project root and install the necessary dependencies:

```bash
npm install
```

### 3. Set Up Environment Variables 🔐

Create an `.env` file in the root directory to store your **OpenWeatherMap** API key. Replace `your_openweather_api_key` with your actual API key:

```bash
REACT_APP_WEATHER_API_KEY=your_openweather_api_key
```

### 4. Run the Application 🚀

To start the application in **development mode**, run:

```bash
npm run dev
```

Once started, the app will be available at [http://localhost:3000](http://localhost:3000).

---

## 🛠️ Technologies Used

- **React** ⚛️
- **Vite** 🏎️
- **OpenWeatherMap API** 🌦️
- **CSS / Tailwind CSS** 🎨 (Optional for Styling)

---

## 🌟 Features

- 🌡️ **Current Weather**: Displays real-time weather data for the searched city.
- 🔍 **City Search**: Users can search for any city to get its weather information.
- 📅 **7-Day Forecast**: Shows the weather forecast for the upcoming 7 days.
- 🎨 **Modern UI**: A sleek, modern user interface for a pleasant user experience.

---

## 🚧 Project Structure

```plaintext
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Forecast.jsx
│   │   ├── Inputs.jsx
│   │   └── TempAndDetails.jsx
│   │   └── TimeAndLocation.jsx
│   │   └── TopButtons.jsx
│   ├── App.jsx
│   ├── index.jsx
│   └── styles.css
├── .env
├── package.json
├── vite.config.js
└── README.md
```

---

## 📦 API Documentation

This project fetches weather data using the **OpenWeatherMap API**. You need to sign up and get an API key from [OpenWeatherMap](https://openweathermap.org/api).

---

## 👥 Contributors

- [Khitish Kumar Nayak](https://github.com/khitishkumar18)
