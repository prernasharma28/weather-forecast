**🌤️ **Weather Information Web Page****

**📜 Overview**
This web page provides current weather information for a specified location. It allows users to enter a location and get details such as temperature, weather condition, humidity, wind speed, and more. The weather data is fetched using the WeatherAPI service.

**🌟 Features**
Search Bar: Users can enter a location to get current weather information. 🌍
Weather Information Display: Shows the current weather condition, temperature (in Celsius and Fahrenheit), humidity, wind speed, wind direction, and more. 🌡️💨
Responsive Design: The page is designed to be responsive, ensuring a good user experience on both desktop and mobile devices. 📱💻

**🛠️ Setup**

**Prerequisites**
A modern web browser 🌐
A valid API key from WeatherAPI 🔑

**Files**
HTML File (index.html): Contains the structure and layout of the web page. 🗂️
CSS Styles: Embedded within the HTML file for styling the page. 🎨
JavaScript: Embedded within the HTML file to handle API calls and dynamic updates. 📜

**Getting Started**
Obtain API Key: Sign up at WeatherAPI to get your API key. 🌧️
Update API Key: Replace 'dc4ea67544ba469eaf364438240609' in the fetchWeather function with your actual API key. 🛠️
Open the Web Page: Open index.html in a web browser. 🌍

**⚙️ Functionality**
Default Location: On page load, the weather information for "India" is displayed. 🇮🇳
Search Function: Enter a location in the search bar and click "Search" to get the current weather for that location. 🔍

**📝 Code Details**
HTML Structure: Defines the layout of the page including the search bar and weather information display area. 🏗️
CSS Styles: Provides styling for the page, including responsiveness for smaller screens. 🖌️

**JavaScript Functions:**
fetchWeather(location): Fetches weather data from the WeatherAPI and updates the display. 🌦️
searchWeather(): Retrieves the value from the search input and calls fetchWeather with it. 🔄

**🛠️ Troubleshooting**
Error Handling: If the API call fails or returns an error, an alert will display the error message. ⚠️
Empty Location Input: If the search bar is empty, an alert will prompt the user to enter a location. 🚫

**🤝 Contribution**
Feel free to contribute by submitting issues or pull requests. Suggestions for improvements are welcome! 💡

**📄 License**
This project is licensed under the MIT License. See the LICENSE file for details. 📜
