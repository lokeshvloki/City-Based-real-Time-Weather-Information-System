# 🌤️ Weather App
A simple, dynamic weather application that retrieves real-time weather data for any city using the OpenWeatherMap API. This project showcases the basics of API integration, JavaScript data handling, and front-end development.

## 📋 Project Overview
The Weather App allows users to:

Search for current weather conditions in any city worldwide
Retrieve key weather metrics, including temperature, humidity, and a general weather description
Interact with a user-friendly interface built using HTML, CSS, and JavaScript
## 🔧 Built With
HTML & CSS: For structure and styling of the web interface
JavaScript: For API interaction and dynamic content rendering
OpenWeatherMap API: Provides access to weather data
## 🚀 Features
Real-Time Data: Pulls live data from the OpenWeatherMap API
City-Based Search: Allows users to search weather data by entering any city name
Error Handling: Displays a user-friendly message if the city is not found
## 📂 Project Structure
```javascript
weather-app/
├── index.html         # HTML structure
├── style.css          # Styling for the app
└── app.js             # JavaScript for API calls and DOM manipulation

## 🛠️ Getting Started
### Prerequisites
Obtain an API key from OpenWeatherMap.
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/weather-app.git
Navigate to the project folder:

bash
Copy code
cd weather-app
Open app.js and add your OpenWeatherMap API key:

javascript
Copy code
const apiKey = "YOUR_API_KEY";
Open index.html in your browser to run the app.

📜 Usage
Enter a city name in the search box.
Click Get Weather to fetch and display current weather data for the selected city.
🔍 Example API Call
plaintext
Copy code
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={YOUR_API_KEY}&units=metric
q: City name (e.g., "London")
appid: Your API key
units: Metric system for temperature in Celsius
🤝 Contributing
Feel free to fork this project and submit pull requests. Contributions are welcome!

## 📄 License
This project is licensed under the MIT License.



```javascript
weather-app/
  index.html  # HTML structure
  style.css   # Styling for the app
  app.js      # JavaScript for API calls and DOM manipulation
