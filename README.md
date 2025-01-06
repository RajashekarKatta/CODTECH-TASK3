Name:RAJASHEKAR KATTA Company:CODETECH IT SOLUTIONS ID: CT08DBJ Domain:Python Programming

Project Overview: Weather Data Fetching and Visualization
This project involves fetching weather data for a specific city from the OpenWeatherMap API, processing it, and visualizing it using Plotly. The goal is to retrieve a 5-day weather forecast, 
extract important details such as temperature, humidity, and pressure, and then present the data in both tabular form and as an interactive graph.

Key Objectives:
Weather Data Fetching:

The script fetches weather data using the OpenWeatherMap API. The endpoint provides a 5-day weather forecast for a given city, including details about temperature, humidity, pressure, and weather description at various time intervals.
Data Processing:

The data returned by the API is parsed, and a pandas DataFrame is created to store the relevant information:
Datetime: The date and time of the forecast.
Temperature: The temperature in Celsius.
Humidity: The humidity percentage.
Pressure: The atmospheric pressure.
Weather Description: A brief description of the weather (e.g., clear sky, few clouds, etc.).
Data Visualization:

The script visualizes the temperature data using Plotly. A line chart is created to show how the temperature changes over the forecasted time period, with markers for each data point.
The chart is interactive, allowing users to hover over points to see detailed information about the temperature at each time.
Workflow:
API Call:

The script makes a request to the OpenWeatherMap API with the provided city name and API key.
It fetches the 5-day forecast data, which includes weather information for every 3-hour interval.
Data Extraction:

The script parses the JSON response from the API and extracts the relevant fields:
Datetime: When the forecast is for.
Temperature, Humidity, Pressure: For each time point.
Weather Description: A brief description of the weather.
Data Display:

The weather data is displayed in a pandas DataFrame for the user to see the raw data.
Chart Visualization:

A Plotly chart is generated to visualize the temperature over the next 5 days.
The x-axis represents the date and time, while the y-axis shows the temperature in Celsius. The chart uses a line graph with markers for each time point.
Technologies Used:
Python Libraries:

Requests: To make HTTP requests to the OpenWeatherMap API.
Pandas: For data manipulation and storage in DataFrame format.
Plotly: For creating interactive charts and visualizations.
OpenWeatherMap API:

Used to fetch weather data for a specified city, including the 5-day forecast.
Visualization:

The data is visualized using Plotly, which provides a flexible and interactive way to present the data.
