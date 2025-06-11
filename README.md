# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*:URMIL RAMESHRAO BHOYAR 

*INTERN ID*:CT06DL1258

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*:6 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION OF TASK 

**API Integration and Data Visualization**

**Project Overview**

This project, **API Integration and Data Visualization**, demonstrates how to fetch real-time weather forecast data from an external public API (OpenWeatherMap) and transform it into a human-friendly, informative format using both tabular representation and graphical visualization. The entire project is developed and executed using **Google Colab**, a powerful cloud-based code editor ideal for data analysis and experimentation.

With this project, users can learn how to connect to APIs, extract relevant structured data, and visualize key parameters such as **temperature**, **min/max temperature**, and **pressure** in a visually appealing manner. The data is fetched specifically for a location (Nagpur, India in this case), and the focus is on forecasting for the upcoming 5 days, particularly at **12 PM** each day.


**Tools & Technologies Used**

 1. *Programming Language*
*Python 3*: The core language used to implement data fetching, processing, and visualization.

 2. *API*
*OpenWeatherMap API*: Used to fetch 5-day weather forecasts including temperature, pressure, and weather descriptions.

 3. *Libraries*
*requests*: For making HTTP requests to fetch data from the weather API.
*datetime*: For parsing and manipulating date/time objects.
*matplotlib*: For plotting temperature and pressure data in graph format.
*json*: (implicitly used) to handle JSON responses from the API.

4. *Code Editor*
*Google Colab*: A free cloud-based Python environment that requires no setup and runs in the browser. It supports Python notebooks and is excellent for data analysis and visualization tasks.

**Workflow**

*Step 1: Fetching Weather Data*
- Use the `requests` module to send a GET request to the OpenWeatherMap API.
- Pass in location coordinates (latitude and longitude), API key, and desired units (metric).
- Receive a JSON response that contains weather data for every 3 hours over 5 days.

*Step 2: Extracting Useful Data*
- Filter the forecast data to include only entries for 12:00 PM each day.
- For each of those entries, extract the following:
  - Date (formatted)
  - Temperature
  - Minimum and Maximum Temperature
  - Humidity
  - Weather Description (like mist, clear sky, etc.)
  - Atmospheric Pressure

*Step 3: Tabular Display*
- Present the extracted data in a neat and readable table format using Python string formatting.
- This helps users quickly scan through multiple weather parameters.

*Step 4: Data Visualization*
- Use `matplotlib` to create a multi-line graph that displays:
  - Daily Temperature
  - Min and Max Temperatures
  - Atmospheric Pressure
- Temperature and pressure are plotted on dual Y-axes for better readability.
- Labels, legends, and rotated x-axis ticks are used to improve clarity.

 **Learning Objectives**

By completing this project, users will learn:
- How to integrate external REST APIs in Python.
- Parsing and handling JSON data.
- Filtering data based on date and time conditions.
- Presenting data in tabular format using Python.
- Creating multi-line plots and dual-axis plots with `matplotlib`.

 **Use Cases and Applications**

*Educational Projects*: Perfect for computer science or data science students learning API integration and visualization.
*Weather Dashboards*: Can be part of a larger dashboard or IoT system where live weather updates are needed.
*News or Utility Apps*: Useful for developers building apps or websites that need weather forecast features.
*Data Journalism*: Journalists and analysts can use this to report on weather trends visually.

 **Future Enhancements**

- Add support for user input to change the city or location.
- Include weather icons in the output.
- Store data in CSV or display using pandas DataFrames.
- Integrate more parameters like wind speed, visibility, etc.
- Build a GUI using Tkinter or deploy on Streamlit for interactivity.

**Code Execution**

Since this project is designed in *Google Colab*, no local installation is necessary. To run the code:
1. Open [Google Colab]((https://colab.research.google.com/drive/1HmpHzrlHsk3wacQUm7YoAjxF4mUY0_x8?usp=sharing)).
2. Paste the Python code into a new notebook.
3. Install required libraries if not already present (`matplotlib`, `requests`).
4. Run the cells and view results directly in your browser.
   
# OUTPUT 
![Image](https://github.com/user-attachments/assets/0aad5cd1-6de9-4a2a-99de-383223a40c36)

![Image](https://github.com/user-attachments/assets/229d84b6-c7c8-457b-af25-1371b6874a62)

![Image](https://github.com/user-attachments/assets/481af59f-4460-4bb2-b33e-498c8a301a95)

![Image](https://github.com/user-attachments/assets/2fc39733-1ece-4d1f-b93e-c3323bf499e6)

![Image](https://github.com/user-attachments/assets/f05d6d36-a802-421e-a0ad-66a013804226)



