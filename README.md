# Weather-forecast-App
Weather App
A modern, user-friendly weather application built using HTML, CSS, and JavaScript that provides real-time weather information by automatically detecting your location or allowing you to search by city name. It uses free and reliable APIs — Open-Meteo for weather data and OpenStreetMap Nominatim for geocoding — so no API keys are required.

Advanced Features
Automatic Location Detection: Uses browser geolocation to fetch current latitude and longitude for precise weather updates.

City Search: Users can enter any city name to get weather details for that location.

Free API Usage: Utilizes Open-Meteo and OpenStreetMap APIs which are free and don’t require API keys.

Detailed Weather Info: Displays temperature (°C), weather condition description, humidity (%), and wind speed (m/s).

Temperature Color Coding: Dynamic UI changes color based on temperature range (hot, warm, cool, cold).

Smooth Animations: Includes fade-in effects, slide-up animations, and a loading spinner for better UX.

Responsive Design: Clean layout and floating circles background make the interface visually appealing on desktop and mobile.

Error Handling: Friendly error messages with shake animation if location or weather data fails.

Manual Refresh: A refresh button to update the weather and location data on demand.

Usage Instructions
Open the app in a modern browser (Chrome, Firefox, Edge, Safari).

Allow location access when prompted to get instant weather updates for your current position.

If location access is denied or not available, enter a city name manually in the input box and click "Get Weather by City".

Weather details including temperature, condition, humidity, and wind speed will be displayed.

Use the "Refresh Location & Weather" button anytime to update the weather for your current location.

The app works entirely on the client side — no backend or server setup is required.

Architecture and Technologies
Frontend Only: Built purely with HTML, CSS, and vanilla JavaScript.

Browser Geolocation API: To fetch user's current latitude and longitude.

Open-Meteo API: Provides weather forecast data in JSON format without requiring API keys.

OpenStreetMap Nominatim API: Reverse geocoding service to convert coordinates into human-readable city and country names.

CSS Animations: Used for loading spinner, result/error animations, and background floating circles for a modern look.

Responsive & Accessible UI: Ensures usability across different screen sizes and devices.

FAQs
Q1: Do I need an API key to use this app?
No! This app uses free public APIs (Open-Meteo and OpenStreetMap) that don’t require any API keys or signups.

Q2: Can I use this app offline?
No. The app fetches real-time weather data from online APIs, so an active internet connection is required.

Q3: Is my location data stored anywhere?
No. Location data is only used locally in your browser to fetch weather information and is not saved or transmitted anywhere else.

Q4: Can I switch temperature units between Celsius and Fahrenheit?
Currently, the app displays temperature in Celsius. Unit conversion can be added as a future enhancement.

Q5: Which browsers are supported?
Modern browsers that support JavaScript and Geolocation API, including Chrome, Firefox, Edge, and Safari.

Future Enhancements (Ideas)
Add multi-day weather forecast with graphical charts.

Allow switching between Celsius and Fahrenheit units.

Include weather icons matching current conditions for better visualization.

Add local storage to save user preferences.

Integrate dark/light mode theme toggle.

Improve mobile responsiveness and accessibility compliance.

Contribution
Contributions are welcome! Feel free to open issues or submit pull requests to improve the app.

Developer:
Developed By Mayank Singh 


License
This project is open source under the MIT License.

Thanks for checking out this project!
Feel free to clone, fork, and modify it to suit your needs
