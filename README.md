# Sweather

Sweather is a weather forecasting web application that provides real-time weather information and displays weather data in a user-friendly interface. It includes features like weather search by city, a weather chatbot, and visual representations of weather forecasts using charts.

## Features

- **City Search**: Search for weather information by city name.
- **Weather Chatbot**: Ask weather-related questions and get instant answers.
- **Forecast Table**: Displays a 5-day forecast with details such as temperature, minimum/maximum, and wind speed.
- **Charts**: Visual representation of weather data in bar, doughnut, and line charts.

## Project Structure

The project consists of the following main files:

### 1. `homepage.html`

The homepage of the application, where users can search for weather data of different cities.

- **Form**: A search input for cities.
- **Responsive Design**: Adjusts for different screen sizes.
- **Sidebar Navigation**: Links to the dashboard and tables pages.

### 2. `table.html`

A page that displays the weather forecast in table format, as well as a chatbot for weather-related queries.

- **Chatbot**: Allows users to ask weather-related questions.
- **Table View**: Displays weather forecast details for the city.

### 3. `index.js`

Handles the dynamic rendering of weather data using APIs.

- **Weather API**: Fetches weather data from OpenWeather API.
- **Chatbot API**: Fetches responses from a chatbot model based on user queries.
- **Table Rendering**: Displays the weather forecast with pagination.
- **Chart Rendering**: Generates different chart types (bar, doughnut, line) using `Chart.js`.

### 4. `homeStyle.css` and `output.css`

Custom CSS files to style the homepage and table pages.

## Technologies Used

- **HTML5 & CSS3**: For structuring and styling the pages.
- **JavaScript (jQuery)**: For handling user interactions, API calls, and DOM manipulation.
- **Tailwind CSS**: For responsive design and utility-based styling.
- **OpenWeather API**: Provides weather data.
- **Chart.js**: Generates dynamic charts to visualize weather data.
- **Google Gemini API**: Powers the chatbot functionality.

## How to Run the Project
