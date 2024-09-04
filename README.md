# Tempobra: Weather forecast website
Solução de dados meteorológicos para o setor de energia.
Tempobra is a weather dashboard that provides real-time weather data for cities across Brazil. The project integrates data from the OpenWeatherAPI and features an interactive chatbot for querying weather conditions. Additionally, the dashboard predicts energy outages based on weather data using machine learning models.

### Features
Real-time weather data: Displays weather information such as temperature, humidity, wind speed, pressure, and cloud coverage for a selected city.
City Search: Search for cities and view the weather conditions of other major cities.
- Interactive Chatbot: The chatbot, "Temai," helps users get weather information through natural language input.
- Weather Forecast: Displays a 5-day weather forecast and a percentage chance of rain.
- Energy Outage Prediction: Uses a machine learning model to predict potential power outages based on weather data.

### Technologies Used
- Frontend: HTML, CSS, JavaScript
- APIs: OpenWeatherAPI for fetching weather data.
- Google Fonts for custom fonts.
- Machine Learning: Neural network model used to predict energy outages based on weather data.
- Backend Infrastructure: Hosted on Google Cloud with data storage and management handled through a datalake.

### How to use
1. Clone the repository:
<code>git clone https://github.com/joaoayu/Weather-forecast-website.git</code>

3. Open the project: Navigate to the project directory and open index.html in your browser.

4. API Setup:
   - You'll need an API key from OpenWeatherAPI. Replace the placeholder API key in the code with your own API key:
     <br>
     <code>const apiKey = 'your-api-key-here';</code>

5. Run the application: Open index.html in your browser to see the weather dashboard in action.
