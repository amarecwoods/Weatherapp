# Weatherapp Base

### Introduction
This is a simple Weather App built using the Tkinter library in Python. It allows users to check the weather for a specific city or zip code. The app makes use of the OpenWeatherMap API to fetch real-time weather data.

### Installation
1. Make sure you have Python installed on your machine.
2. Install the required Python packages using the following command:
   ```bash
   pip install requests pillow
   ```
3. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder `api_key` in the code with your actual API key.

### How to Use
1. Run the application by executing the script in a Python environment.
   ```bash
   python weather_app.py
   ```
2. The app will open, and you will see a simple interface with an entry field to input the city or zip code and a dropdown menu to select the search type (City or Zip Code).
3. Click the "Enter" button to retrieve the weather information.
4. A pop-up window will display the city name, temperature in Fahrenheit, and a brief weather description.
5. The app will also display an image representing the current weather condition.

### Weather Icons
The app uses placeholder images for different weather conditions. Replace these placeholder paths in the `get_weather_image_path` method with your actual image paths for a more visually appealing experience.

### Notes
- The app is a simple demonstration and can be extended with additional features such as multiple city forecasts, hourly forecasts, and more.
- Make sure to handle exceptions and errors gracefully, especially when dealing with API requests.
- Customize the UI, color schemes, and images to fit your preferences.

### Credits
- Tkinter: [https://docs.python.org/3/library/tkinter.html](https://docs.python.org/3/library/tkinter.html)
- OpenWeatherMap API: [https://openweathermap.org/api](https://openweathermap.org/api)
- Pillow (PIL Fork): [https://pillow.readthedocs.io/](https://pillow.readthedocs.io/)

Feel free to modify and enhance the code as needed for your specific requirements.
