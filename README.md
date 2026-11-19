# 🌤️ Weather App

A clean and responsive Weather App built using **HTML, CSS, and JavaScript** with the **OpenWeatherMap API**. Users can search any city by clicking the search button or pressing **Enter** to view live temperature, humidity, wind speed, and weather conditions.

## ✨ Features

- Search weather by city name using either the search icon or the **Enter** key.
- Displays live temperature in Celsius (`°c`), humidity (`%`), and wind speed (`km/h`).
- Dynamic weather icons for `Clouds`, `Clear`, `Rain`, `Drizzle`, `Mist`, `Haze`, and `Fog`.
- Error message display (`Invalid city name`) for invalid or unknown city inputs.
- Responsive card layout with gradient styling.

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| HTML5 | App structure, search input, error box, and weather layout |
| CSS3 | Flexbox layout, gradient card design, and responsive styling |
| JavaScript | Fetching OpenWeatherMap API data, DOM updates, and event handling |
| OpenWeatherMap API | Real-time weather data retrieval |

## 📁 Project Structure
Weather-App/
│
├── index.html
├── style.css
├── search.png
├── rain.png
├── clouds.png
├── clear.png
├── drizzle.png
├── mist.png
├── humidity.png
└── wind.png

## Installation

Clone the repository using the following command:
```
git clone https://github.com/shiprasonal/Weather-App.git
```
Open the cloned project folder and launch `index.html` in your web browser.

**Repository Link:** [Weather App](https://github.com/shiprasonal/Weather-App)

## 🔎 How to Use

1. Type a city name (for example, `Patna` or `Muzaffarpur`) into the search box.
2. Click the **Search** button or press **Enter**.
3. View the updated weather icon, temperature, humidity, and wind speed.
4. Enter an invalid city name to see the error message.

## 💡 What I Learned

- Fetching real-time API data with JavaScript `fetch()` and `async`/`await`.
- Handling API response status codes (such as `404`) and error states.
- Manipulating DOM elements dynamically to update temperature, humidity, wind speed, and icons.
- Supporting both button click and `Enter` keyboard events for user input.
- Building a clean, responsive card UI using HTML and CSS.

## 👩‍💻 Author

**Shipra Sonal**

[GitHub](https://github.com/shiprasonal) · [LinkedIn](https://www.linkedin.com/in/shipra-sonal-554a50258)

---

⭐ If you find this project interesting, feel free to explore the repository!
