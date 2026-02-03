# Minimal Weather

A lightweight, privacy-focused weather application specifically designed for the **Minimal Phone** and other e-paper devices. Minimal Weather leverages the Open-Meteo API to provide hyper-local forecasts and air quality data in a high-contrast, battery-efficient interface.

---

## 📱 Screenshots

| | |
| :---: | :---: |
| ![Homescreen](https://i.postimg.cc/mgD9VFVF/Screenshot_20260203_232608.png) | ![Weathersummary](https://i.postimg.cc/FHRSGJGc/Screenshot_20260203_232617.png) |
| ![forecasts](https://i.postimg.cc/XYJ5xyx5/Screenshot_20260203_232631.png) | ![locator](https://i.postimg.cc/JznXKBKk/Screenshot_20260203_232650.png) |
| ![Menu1](https://i.postimg.cc/YC9F8m8Y/Screenshot_20260203_232700.png) | ![Menu2](https://i.postimg.cc/t4T6DVDF/Screenshot_20260203_232741.png) |

---

## ✨ Key features

### 🌤️ Comprehensive forecasts
Accurate weather data powered by Open-Meteo, presented without clutter:
* **Current conditions:** Real-time temperature, weather codes, and dynamic iconography.
* **Smart summary:** An algorithmic "Assistant" that generates advice (e.g., "Wear a warm coat," "Don't forget an umbrella") based on temperature, wind, UV, and precipitation logic.
* **Hourly scroll:** 24-hour horizontal scroll for immediate planning.
* **Weekly outlook:** 7-day forecast grid with High/Low temps and precipitation probability.

### 🍃 Wellbeing features
Goes beyond simple temperature with detailed environmental metrics:
* **Air quality:** Real-time US AQI readings.
* **Pollen tracker:** Specific levels for Tree, Grass, and Ragweed pollen.
* **Pollutants:** Monitoring for Dust (PM10), Fine Dust (PM2.5), and Ozone (O₃).
* **Atmospherics:** UV Index, Humidity, Pressure, and Wind Speed/Direction.

### 📍 Location management
* **Multiple cities:** Save and manage an unlimited number of locations.
* **Geolocation:** One-click "Your Location" setup using the device's GPS.
* **Privacy first:** All location data is stored locally in `LocalStorage`. No external servers track your movement.

---

## ⌨️ QWERTY Keyboard Support

Designed for the Minimal Phone's physical keyboard to allow navigation without touching the screen:

| Key | Action |
| :--- | :--- |
| <kbd>SPACE</kbd> | Cycle through saved **locations** |
| <kbd>R</kbd> | **R**efresh current weather data |
| <kbd>L</kbd> | Open the **L**ocations / Settings Menu |
| <kbd>A</kbd> | **A**dd a new city (Open Search) |
| <kbd>↵</kbd> | Confirm search / Select item |
| <kbd>⌫</kbd> | Close active popups (Back) |

---

## 🛠️ Customization & tools

* **E-paper optimization:** High-contrast Black & White UI designed to minimize ghosting and maximize readability in direct sunlight.
* **Theme support:** Choose between **Light**, **Dark**, or **Auto** (follows system preferences).
* **Sunrise/Sunset:** Dynamic tracking based on the current time of day.
* **Offline resilience:** The app shell is PWA-ready (Service Worker compatible) for faster loading.

---

## 🚀 Technical details

* **Version:** `v0.1 (19) Beta`
* **Data source:** [Open-Meteo API](https://open-meteo.com/) (Free, Non-commercial, No API Key required).
* **Stack:** Vanilla HTML/CSS/JS. No heavy frameworks - so fast and reliable.
* **Storage:** `LocalStorage` persistence for user preferences and city lists.
* **Privacy:** Anonymous API calls. No user data collection.

---

## 📥 Installation

1. Download the latest **APK** wrapper.
2. Install to your **Minimal Phone**.
3. Enjoy!

[![Download](https://img.shields.io/badge/↓_Download-v0.1-000000?style=for-the-badge&logoColor=white&labelColor=black&color=white)](https://dl.dropbox.com/scl/fi/qsqpmcu4l7ohda2rdjafk/Minimal-Weather-0.1.apk?rlkey=mx84nsx9vu7vtwyl4s2t5mw1p&st=zj9axr3s)
