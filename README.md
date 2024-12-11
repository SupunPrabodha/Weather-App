# 🌤️ Weather App

This is a simple weather application built with HTML, CSS, and JavaScript that allows users to check the current weather conditions by entering a city name. It fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api).

## 🌐 Demo

You can access the live demo of the app here: **[Live Demo URL]**

---

## 📸 Screenshots

### Main Interface

![Weather App Screenshot](images/demo.png) <!-- Replace with actual screenshot path if available -->

---

## 🛠️ Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling the interface.
- **JavaScript**: Logic for fetching and displaying weather data.
- **OpenWeatherMap API**: To get real-time weather data.

---

## 📥 How to Clone and Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SupunPrabodha/weather-app.git
   ```

2.   Navigate to the project folder:

bash
Copy code
cd weather-app
Open the index.html file in your browser:

bash
Copy code
open index.html
Alternatively, drag and drop index.html into your browser.

🔑 API Key Configuration
This app uses the OpenWeatherMap API. To make the app work with your own API key:

Visit OpenWeatherMap and sign up to get a free API key.

Replace the apiKey in index.html with your own key:

javascript
Copy code
const apiKey = "YOUR_API_KEY_HERE";
💡 How to Use
Enter the city name into the input field.
Click the search button or press Enter.
View the current temperature, humidity, wind speed, and weather icon for the selected city.
If the city name is incorrect, an error message will be displayed.
📂 Project Structure
lua
Copy code
weather-app/
│-- index.html
│-- style.css
│-- images/
│   ├── search.png
│   ├── clouds.png
│   ├── clear.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
└-- README.md
📝 License
This project is licensed under the MIT License.

🙌 Acknowledgments
OpenWeatherMap for providing the weather API.
If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request!

⭐ If you like this project, don't forget to star it! ⭐
