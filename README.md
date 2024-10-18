
# 🌤️ Weather Dashboard - React + Vite

This project is a **Weather Dashboard** application that allows users to search for cities and view current weather information along with a 7-day forecast. It's built using **React** with **Vite** for fast development, and it fetches weather data from **OpenWeatherMap** API. ⛅

## 📸 Screenshots

### Home Screen 🌍
![Screenshot 2024-10-18 235537](https://github.com/user-attachments/assets/6d0862ee-87fa-443a-b05d-5469332c6de0)

### Search City 🔎
![Screenshot 2024-10-18 235551](https://github.com/user-attachments/assets/a8fa9d18-88f0-4043-9d9b-3ff7fcf6a87f)

### 7-Day Forecast 📅
![Screenshot 2024-10-18 235813](https://github.com/user-attachments/assets/32b2f7ab-bc40-4193-99dc-92c811322ff0)

### Current Location Detection and Weather Report ⚡
![Screenshot 2024-10-18 235953](https://github.com/user-attachments/assets/1fc0b3ce-aae5-4e2e-866f-b48538cc5df2)

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
