# Weather App

A simple and clean web application that provides real-time weather information for any city. Built with vanilla HTML, CSS, and JavaScript, this project fetches live data from the OpenWeatherMap API to display current weather conditions, including temperature, humidity, and wind speed.

![Weather App Screenshot](https://i.imgur.com/8fS2Zqb.png)
*(Feel free to replace this with a screenshot of your own project)*

---

## Features

* **City Search:** Search for the current weather of any city around the world.
* **Real-time Data:** Displays up-to-date weather information:
    * Temperature in Celsius (°C).
    * Humidity percentage (%).
    * Wind speed in km/h.
* **Dynamic Icons:** The weather icon changes dynamically based on the current conditions (e.g., Clouds, Rain, Clear, Mist, etc.).
* **User-Friendly Interface:** Clean, simple, and responsive card-based design that looks great on any screen size.
* **Interactive Search:** Users can initiate a search either by clicking the search button or by pressing the "Enter" key.

## Technology Stack

* **HTML5:** Used for the basic structure and content of the web page.
* **CSS3:** Used for styling the application, including the layout, colors, and responsive design.
* **JavaScript (ES6+):** Used for the application's logic, including:
    * Handling user input.
    * Making asynchronous API calls using `async/await` to fetch data.
    * Dynamically updating the DOM to display the fetched weather information.

## API Used

* **OpenWeatherMap API:** The project uses the [OpenWeatherMap One Call API](https://openweathermap.org/api) to get live weather data for different locations.

---

## Setup and Installation

To run this project on your local machine, follow these simple steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```

2.  **Get an API Key**
    * Go to the [OpenWeatherMap website](https://openweathermap.org/api) and create a free account.
    * Navigate to the 'API keys' tab and get your unique API key.

3.  **Update the API Key in the Code**
    * Open the `script.js` file.
    * Find the `appKey` variable and replace the existing key with your own API key.
    ```javascript
    // In script.js
    const appKey = `&appid=YOUR_API_KEY_HERE`;
    ```

4.  **Run the Application**
    * Simply open the `index.html` file in your web browser to see the application in action.
