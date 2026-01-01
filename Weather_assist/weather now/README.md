# 🌦️ WeatherNow AI

WeatherNow AI is a simple and user-friendly web application that provides **real-time weather information** for any city and enhances it with **AI-generated, human-friendly explanations**.

The goal of this project is to combine **accurate weather APIs** with **Generative AI** to make weather data easier to understand and more useful for users.

---

## 🚀 Project Flow

1. **User enters a city name**
2. The app sends the city name to a **Weather API**
3. The Weather API returns **real-time weather data**
4. This weather data is sent to **AI (Gemini)**
5. AI converts raw data into a **natural, human-readable response**
6. The UI displays both:
   - Weather details
   - AI-generated explanation

---

## 🧠 Why AI is Used

Weather APIs return **raw, technical data** (temperature, condition, humidity).  
AI is used to:
- Convert technical data into **natural language**
- Provide **weather-aware suggestions**
- Improve overall **user experience**

> Example:  
> *“It’s a sunny 32°C day in Bhopal — a good time to enjoy outdoor activities.”*

---

## 🛠️ Technologies Used

### Frontend
- **React.js** – Component-based UI
- **Vite** – Fast development build tool
- **Tailwind CSS** – Responsive styling
- **Framer Motion** – Smooth UI animations

### APIs
- **Open-Meteo API**
  - City geocoding (latitude & longitude)
  - Real-time weather data
- **Google Gemini API**
  - AI-generated natural language responses

---

## 🔄 Data Flow Diagram (Conceptual)

User Input (City)
↓
Geocoding API (City → Coordinates)
↓
Weather API (Real-time Weather Data)
↓
Gemini AI (Human-friendly Explanation)
↓
UI Display

👨‍💻 Author

Priyanshu Kumar
Frontend & Full Stack Developer