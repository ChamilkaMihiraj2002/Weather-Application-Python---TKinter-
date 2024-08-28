# Weather-Application-Python---TKinter-

My application is a simple **Weather App** built using Python's `Tkinter` library for the graphical user interface (GUI). The app fetches and displays the current weather information for a specified city by using the **OpenWeatherMap** API.
![image 1](https://github.com/user-attachments/assets/f5eeea3a-7934-4030-a1c6-2908944cd331)

### Key Features:
- **Graphical User Interface:** The app uses `Tkinter` to create a user-friendly interface with a text input field and buttons.
- **Weather Data Fetching:** The app fetches current weather data (temperature, weather condition, and humidity) for any city by making HTTP requests to the OpenWeatherMap API.
- **Error Handling:** The app includes basic error handling to manage issues such as network errors or invalid city names.
- **Display:** The fetched weather data is displayed within the GUI.
  
![Main GUI](https://github.com/user-attachments/assets/055ec604-0b22-4961-a57b-bffbe5cac7b3)

### Project Structure:
- **Main Application (Weather App):**
  - The application has a single main window that allows users to input a city name and get the current weather data.
  - It includes a small weather icon at the top, the city input field, and the weather details (temperature, weather conditions, and humidity).
  
- **APIs:**
  - The application uses the OpenWeatherMap API to fetch real-time weather data.

### Requirements:
- **Python:** Ensure that Python is installed on your system.
- **Modules:**
  - `tkinter` (Python's built-in module for GUI applications)
  - `PIL` (Python Imaging Library - to handle image processing)
  - `requests` (to make HTTP requests to the weather API)

### Installation Guide:

To get started with this application, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Install required modules:**
   You need to install the necessary Python modules listed in the `requirements.txt` file. Run the following command to install them:
   ```bash
   pip install -r requirements.txt
   ```
   Alternatively, you can install the required modules individually:
   ```bash
   pip install Pillow
   pip install requests
   ```

3. **Add your OpenWeatherMap API key:**
   - You need an API key from OpenWeatherMap to use this app. Sign up [here](https://openweathermap.org/appid) if you don't have an account.
   - Once you have the API key, replace the `api_key` variable in the code with your actual API key.

4. **Run the Application:**
   After setting up everything, you can run the application using:
   ```bash
   python app.py
   ```

### Example Usage:

1. Enter the name of a city in the input field.
2. Click the **Get Weather** button.
3. The application will display the weather information such as temperature, weather conditions, and humidity.

### Screenshots:
You can add screenshots of the app here to showcase the UI.

### Acknowledgements:
- **OpenWeatherMap API** for providing the weather data.
- **Pillow** for image handling.
- **Tkinter** for the GUI components.

### License:
This project is licensed under the MIT License. You are free to use and modify it as you wish.

---
