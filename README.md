# 🌤️ Weather App

This is a simple weather application built with **HTML, CSS, and JavaScript** that allows users to check the current weather conditions by entering a city name. It fetches real-time weather data from the [OpenWeatherMap API](https://openweathermap.org/api).

## 📸 Screenshots

### Main Interface

![image](https://github.com/user-attachments/assets/cf1a2a17-826d-4d6e-9a5d-ed2ab276fc0d)

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

2. **Navigate to the project folder**:

   ```bash
   cd Weather App
   ```   
3. **Open the `index.html` file in your browser**:

   ```bash
   open index.html

Alternatively, drag and drop `index.html` into your browser.

---

##🔑 API Key Configuration

This app uses the **OpenWeatherMap API**. To make the app work with your own API key:

Visit **OpenWeatherMap** and **sign up** to get a free API key.

Replace the `apiKey` in `index.html` with your own key:
```bash
const apiKey = "YOUR_API_KEY_HERE";
```

---

## 💡 How to Use
1. **Enter the city name** into the input field.
2. Click the **search button** or **press Enter**.
3. View the current **temperature, humidity, wind speed,** and **weather icon** for the selected city.
4. If the city name is incorrect, an error message will be displayed.

---

## 📂 Project Structure
```bash
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
```

---

## 🙌 Acknowledgments

OpenWeatherMap for providing the weather API.
If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request!

⭐ If you like this project, don't forget to star it! ⭐
