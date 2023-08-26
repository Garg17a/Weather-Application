# Weather Application

I built Weather Application using the Tkinter library in Python. This application allows users to select a city from a dropdown menu, retrieve weather data for that city using the OpenWeatherMap API, and display the weather information on the graphical user interface (GUI).

The Weather Application is a desktop program that provides real-time weather information for selected cities in India.

Features:-

City Selection: Users can select a city from a dropdown menu containing a list of states and union territories in India.

Weather Details: The application fetches weather data using the OpenWeatherMap API and displays the following information:

-->Weather climate (e.g., "Clouds," "Rain," etc.).
-->Weather description (e.g., "Partly cloudy," "Light rain," etc.).
-->Temperature in Celsius (converted from Kelvin).
-->Atmospheric pressure.

Components:-

GUI Interface: The GUI is designed using the Tkinter library, offering a user-friendly interface. It consists of the following elements:

-->A title label "Weather APP" at the top.

-->A dropdown combobox for selecting the desired city.

-->Labels to display weather information, including climate, description, temperature, and pressure.

-->A "Done" button that triggers the fetching and display of weather data.


Data Retrieval: The application makes an HTTP request to the OpenWeatherMap API using the requests library. It retrieves weather data in JSON format based on the selected city.


Dependencies:-

-->Tkinter: The standard GUI library for Python.

-->requests: A library for making HTTP requests, used here to fetch weather data from the OpenWeatherMap API.

-->ttkthemes: A library for themed Tkinter widgets, used for styling the dropdown combobox.


API Key:--

To use the application, you need an API key from OpenWeatherMap. Replace the appid parameter in the API request URL with your actual API key.


CONCLUSION:- 

The Weather Application project is a simple yet effective demonstration of how Python's Tkinter library can be used to create a graphical user interface for fetching and displaying real-time weather data using the OpenWeatherMap API. The project provides a valuable learning experience in various aspects of programming, including GUI development, API integration, data parsing, and user interaction.

By allowing users to select a city and retrieve weather information, this application showcases the power of combining different technologies to create a functional tool. The project's key components, such as the GUI elements, data retrieval logic, and API key integration, come together to form a cohesive application that serves a practical purpose.


