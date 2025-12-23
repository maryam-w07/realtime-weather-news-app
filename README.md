# Weather & News App

A Python Flask web app that provides real-time weather updates and related news for any city. Users can enter a city name to get the current weather, temperature, condition, and the latest related news articles. The app also displays an interactive temperature map from OpenWeatherMap.

## Features

- Fetches **current weather data** for any city using OpenWeatherMap API.
- Retrieves **related news articles** using GNews API.
- Displays an **interactive temperature map** for the selected city.
- Web interface built with **Flask** for simple user interaction.
- Handles API keys securely using **.env** files.

## Tech Stack

- Python 3.x
- Flask
- Requests
- JSON
- OpenWeatherMap API
- GNews API
- dotenv

## How to Run

1. Clone the repository:
   git clone https://github.com/maryam-w07/weather-news-app.git
   cd weather-news-app
   
2. Install dependencies:
   pip install -r requirements.txt
   
3. Create a .env file and add your API keys:
   X-RapidAPI-Key=your_key_here
   NEWS_API=your_news_key_here
   API_KEY_CURRENT=your_weather_key_here
   
4. Run the app:
   python app.py
   Open your browser at http://127.0.0.1:5000/ and start using the app.
