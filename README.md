Overview
This is a React-based Weather App that provides real-time weather updates for any city using the OpenWeather API. Users can enter a city name and get the current temperature, weather conditions, wind speed, and weather icon.

Features
✅ Real-Time Weather Data – Fetches live weather updates from OpenWeather API
✅ Search Any City – Enter any city name to get weather details
✅ Temperature & Conditions – Displays temperature in Celsius and weather description
✅ Weather Icon – Shows an icon representing current weather conditions
✅ Wind Speed – Displays wind speed in meters per second
✅ Responsive UI – Clean and user-friendly interface

Technologies Used
🔹 React.js
🔹 OpenWeather API
🔹 Axios for API Requests
🔹 CSS for Styling

Installation & Setup
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/weather-app.git
cd weather-app
Install dependencies:
bash
Copy
Edit
npm install
Set up API Key:
Create a .env file in the root directory
Add the following line (replace your_api_key_here with your actual API key):
ini
Copy
Edit
REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
Run the App:
bash
Copy
Edit
npm start
Open http://localhost:3000/ to view in your browser.
API Usage
The app fetches weather data using the OpenWeather API with the following endpoint:

bash
Copy
Edit
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
Future Enhancements 🚀
🔹 7-day Weather Forecast
🔹 Interactive City Map (Google Maps API)
🔹 Dark Mode UI
🔹 Weather Alerts & Seasonal Trends
