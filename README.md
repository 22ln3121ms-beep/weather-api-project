project:
  title: Weather API App
  description: >
    A web-based Weather Application built using HTML, CSS, and JavaScript.
    It integrates the OpenWeather API to fetch real-time weather data
    including temperature, humidity, weather icons, and a 5-day forecast.
  purpose: Solo requirement for Elective 3 (ELEC3)

author:
  name: Mark John Paul Villacorta
  github_username: 22ln3121ms-beep
  course: BS Information Technology
  year_section: 4-BSIT-D
  campus: Pangasinan State University - Lingayen Campus
  subject: Elective 3
  project_type: Solo Project

features:
  - Search weather by city name
  - Display current temperature
  - Display humidity
  - Weather condition icons
  - 5-day weather forecast
  - Automatic day and night theme
  - Loading indicator
  - Input validation
  - Error handling
  - Responsive card-based layout

technologies:
  - HTML
  - CSS
  - JavaScript
  - OpenWeather API
---

project_structure:
  root:
    - index.html
    - style.css
    - script.js
    - README.md
    - .gitignore
    - weather-api-project.yml
  ignored_files:
    - config.js
    
    ---
installation:
🔗 CLONE REPOSITORY LINK 
 ```bash
git clone https://github.com/22ln3121ms-beep/weather-api-project.git
    
```
Navigate to the project folder:

 ```bash
cd weather-api-project

```
▶️ How to Use

Enter a city name (e.g., Manila, Tokyo, London)

Click the Get Weather button

View the current weather details

Scroll to see the 5-day forecast

Observe automatic day/night theme changes

------
📂 Project Structure
weather-api-project/
├── index.html
├── style.css
├── script.js
├── config.js   (ignored in GitHub)
├── .gitignore
└── README.md

---
🚨 Error Handling

The application properly handles:

Empty input fields

Invalid city names

Failed API requests

API authorization issues

Loading state during data fetching

---
📜 License

This project is for educational purposes only.

---
⭐ Acknowledgment

OpenWeather for providing the free public API

Instructor and course materials for guidance
