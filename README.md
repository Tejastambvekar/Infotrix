# Infotrix
This Python-based command-line application is designed to help users check weather information for various cities, manage a list of favorite cities, and enable an auto-refresh feature for up-to-date weather data. Here's a breakdown of the key features and how the application works:

1. Checking Weather by City Name:
  - Users can enter the name of a city to retrieve current weather information.
  - The application makes an API request to OpenWeatherMap, fetching details such as temperature, weather description, humidity, and wind speed for the specified city.
  - The weather data is displayed in the command-line interface for the user to see.

2. CRUD Operations on Favorite Cities:
  - Users can maintain a list of favorite cities.
  - They can add a city to their favorites using a simple command.
  - Similarly, users can remove a city from their list of favorites.
  - The application provides a way to list all favorite cities and their associated weather data.

3. Auto-Refresh Feature:
  - Users can enable an auto-refresh feature for a specific city.
  - The application periodically updates the weather data for the selected city every 15-30 seconds.
  - This ensures that users always have the latest weather information for their chosen city.

4. Error Handling and Data Validation:
  - The application includes error handling to provide informative messages in case of issues, such as invalid city names or API request errors.
  - Data validation ensures that users receive accurate and relevant weather data.

5. API Integration:
  - The application makes use of the OpenWeatherMap API to retrieve weather information. Users need to provide their own API key for authentication.

6. User-Friendly CLI:
  - The command-line interface offers a user-friendly experience with clear options and prompts.
  - Users can navigate through the application easily to check weather, manage their favorite cities, and set up auto-refresh.

This Python Weather Checking Application empowers users to stay informed about weather conditions in their favorite cities, provides a simple way to manage their preferences, and automatically updates weather data to ensure accuracy. The application is flexible and can be expanded to include additional features based on specific user requirements.
