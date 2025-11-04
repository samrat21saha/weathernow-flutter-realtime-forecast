# 🌦️ WeatherNow – Real-Time Weather Forecast App

A sleek and responsive Flutter application that provides **real-time weather updates** and **forecast visualization** using REST APIs.  
Designed to deliver accurate, location-based insights with an intuitive and minimalist user experience.

---

## 🚀 Features
- 📍 **Auto Location Detection** – Fetches weather data using device GPS.  
- 🌡️ **Real-Time Forecast** – Displays temperature, humidity, pressure, and wind speed.  
- 🕒 **7-Day Weather Predictions** – Visual trend charts with animated graphs.  
- 🎨 **Dynamic UI** – Changes background themes based on live weather conditions.  
- 🌐 **API Integration** – Consumes OpenWeatherMap API for global coverage.  
- 📲 **Responsive Layout** – Adaptive design for all screen sizes and orientations.

---

## 🏗️ Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| Frontend | Flutter (Dart) |
| Backend | OpenWeatherMap REST API |
| State Management | Bloc |
| UI Design | Custom Widgets, Lottie Animations |
| Geolocation | geolocator & permission_handler packages |

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/samrat21saha/weathernow-flutter-realtime-forecast.git

# Navigate to the project
cd weathernow-flutter-realtime-forecast

# Get dependencies
flutter pub get

# Add your API Key in lib/config/api_key.dart
const String apiKey = "YOUR_API_KEY";

# Run the app
flutter run
```

## 📸 Screenshots

- Signup/Login Page
- <img width="1024" height="1024" alt="Signup_Login" src="https://github.com/user-attachments/assets/1e5db388-fb88-48f6-aeb2-3d1d1e066518" />

- Home Page (Current Location weather)
- <img width="1024" height="1024" alt="Home (Current Location weather)" src="https://github.com/user-attachments/assets/6661dbcd-428c-43bf-9297-599a3f883234" />

- Search City Page
- <img width="1024" height="1024" alt="Search Cities" src="https://github.com/user-attachments/assets/3deadbb0-0d8d-4486-aa6d-cbac3f554cc5" />

- Weather Map Page
- <img width="1024" height="1024" alt="Weather Map page" src="https://github.com/user-attachments/assets/141bade9-de48-48b5-a4a0-05456c97215e" />

- 7 Days Forecast Page
- <img width="1024" height="1024" alt="7 Days Forecast" src="https://github.com/user-attachments/assets/757a0fa1-ab1e-4e7c-939e-2cac11b7c277" />


## 🧩 Architecture Overview
- Bloc Pattern – Decouples UI, business logic, and API calls.

- Repository Layer – Handles all API communications and data parsing.

- Error Handling & Caching – Ensures robust, low-latency weather updates.

- Folder Structure Example:

css
Copy code
lib/
 ┣ blocs/
 ┣ models/
 ┣ repositories/
 ┣ screens/
 ┣ widgets/
 ┗ main.dart


## 🧠 Future Enhancements
- Google Maps integration for location search
- Air quality & pollution index metrics
- AI-based “Comfort Index” based on temperature + humidity









