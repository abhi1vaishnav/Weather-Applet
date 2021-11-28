# Weather App
A weather app to display temperature difference chart between two cities.

## Building Materials
Flask
OpenWeatherMap API
Fetch API
Chart.js

## Usage
Change the API Key
Run script.py
Open http://127.0.0.1:8080

## Changing the API key
Go to https://openweathermap.org
Sign-up for free and verify account
Click on your username and go to My API keys
Type the name of key and click generate
Copy the key
Make a .env file in the root folder
Add "APIKEY={yourAPIKEYwithoutcurlybraces}"

## Folder Structure
--Root
  |- temp.py (Gets temperature)
  |- keep_alive.py (Flask server)
  |- templates
    |- public
      |- index.html (View)
      |- data.json (Database)
  |- script.py (Main file that runs everything)
  |- LICENSE
  |_ README.md

### WARNING ###
Don't disclose your API key to anyone it can be a privacy and security threat!
