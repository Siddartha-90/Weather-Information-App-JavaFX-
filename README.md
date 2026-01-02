# 📌 Weather Information App (JavaFX)

## 🎓 Academic Context

This project was developed as part of **Unit 8 – Programming 2** at the **University of the People**. It fulfills the course requirement of building a JavaFX-based application with API integration and demonstrates core object-oriented programming concepts.

---

## 1️⃣ Overview

The Weather Information App is a JavaFX-based graphical application that retrieves **real-time weather data** and a **short-term forecast** using the **OpenWeatherMap API**. Users can search weather information by city name, switch between temperature units, view a search history with timestamps, and experience dynamic background changes based on the time of day.

---

## 2️⃣ Features Implemented (Mapped to Requirements)

| Requirement        | Status | Description                                   |
| ------------------ | ------ | ---------------------------------------------- |
| API Integration    | ✅      | OpenWeatherMap API                           |
| JavaFX GUI         | ✅      | JavaFX-based user interface                  |
| User Input         | ✅      | City name input via TextField                |
| Weather Display    | ✅      | Temperature, humidity, wind speed, condition |
| Weather Icons      | ✅      | Icons provided by OpenWeatherMap             |
| Forecast           | ✅      | Short-term (5-day / 3-hour) forecast         |
| Unit Conversion    | ✅      | Celsius / Fahrenheit                         |
| Error Handling     | ✅      | Invalid city name & API failure handling     |
| Search History     | ✅      | Timestamped city search history              |
| Dynamic Background | ✅      | Automatic Day / Night theme                  |

---

## 3️⃣ Prerequisites

* Java JDK **11 or higher**
* JavaFX SDK
* Internet connection
* Free OpenWeatherMap API key
  👉 [https://openweathermap.org/api](https://openweathermap.org/api)

---

## 4️⃣ Project Structure

```
WeatherApp/
│
├── src/
│   ├── WeatherApp.java
│   ├── WeatherService.java
│   ├── WeatherData.java
│
├── resources/
│   ├── day.css
│   ├── night.css
│
├── README.md
```

---

## 5️⃣ Application Components

* **WeatherApp.java** – Main JavaFX application and GUI logic
* **WeatherService.java** – Handles REST API communication and JSON parsing
* **WeatherData.java** – Model class representing weather data
* **CSS Files** – Provide dynamic styling for day and night modes

---

## 6️⃣ Dynamic User Interface

The application automatically applies:

* **Day theme** between 06:00 and 18:00
* **Night theme** between 18:01 and 05:59

This feature improves usability and demonstrates JavaFX CSS styling.

---

## 7️⃣ How to Run the Application

1. Install **Java JDK 11 or higher**
2. Install and configure **JavaFX SDK**
3. Replace `YOUR_API_KEY_HERE` in `WeatherService.java` with your OpenWeatherMap API key
4. Compile and run `WeatherApp.java`

---

## 8️⃣ API Used

* **OpenWeatherMap API**
  [https://openweathermap.org](https://openweathermap.org)

---

## 9️⃣ Learning Outcomes

* JavaFX GUI development
* REST API integration
* JSON data processing
* Object-Oriented Programming (OOP)
* Exception and error handling
* Separation of concerns (UI, service, model)

---

## 👤 Author

**Siddartha Shankar Tanchangya**
University of the People
Programming 2 – Unit 8
