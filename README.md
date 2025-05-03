## Project Goal

This Java application retrieves and displays current weather information for a user-specified location using a public weather API. The goal is to demonstrate API integration, user interface development in JavaFX, data parsing, and persistent user interaction in a desktop application.

## Project Structure

## Project Structure

```text
src/main/java/
├── Alert         - Shows a confirmation window for account deletion
├── Components    - Contains all UI components and their interactions
├── DB            - Handles user database (accounts, favorites, etc.)
├── Exceptions    - Custom exception classes for handling edge cases
├── Serwer        - Core logic: API connection and weather filtering
```



## Features

- API integration – Connects to OpenWeatherMap to fetch live weather data.
- User interface – Developed using JavaFX for a desktop experience.
- User database – Allows login, account creation, and saving favorite locations.
- Location detection – Detects user's current location to display weather alerts.
- Exception handling – Covers issues like internet disconnection or incorrect login credentials.
- Location-based weather display – Filters and shows weather based on location.
- Real-world map – Lets users click on the map or input coordinates to check weather anywhere.

## How to Run
For example in IntelijIDEA run Main.java file.

### Requirements

- Java 8 or higher
- Maven
- API key from a weather data provider ([OpenWeatherMap](https://openweathermap.org/api))


