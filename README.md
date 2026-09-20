# Weather CLI App

A simple command-line application that fetches and displays current weather conditions for any city, using the OpenWeatherMap API.

## Features

- Search current weather by city name
- Displays temperature, weather description, and "feels like" temperature
- API key managed securely via environment variables

## Tech Stack

- Python
- [Requests](https://docs.python-requests.org/) — for HTTP calls to the OpenWeatherMap API
- [python-dotenv](https://pypi.org/project/python-dotenv/) — for environment variable management

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Safae-ElHamri/weather-cli-app.git
cd weather-cli-app
```

### 2. Create a virtual environment and install dependencies

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Set up your API key

Create a `.env` file in the project root:

```
API_KEY=your_openweathermap_api_key_here
```

Get a free API key at [OpenWeatherMap](https://openweathermap.org/api).

### 4. Run the app

```bash
python weather.py
```

You'll be prompted to enter a city name, and the app will display the current weather conditions.

## Example

```
Please enter a city name:
Tangier

Current weather for Tangier:

The temp is 74.3°

Clear sky and feels like 73.1°
```

## What I Learned

- Working with external REST APIs and parsing JSON responses
- Managing sensitive credentials securely with environment variables (`.env` + `.gitignore`)
- Structuring a small Python CLI tool with clean, readable output

## Author

**Safae El Hamri**
[LinkedIn](https://www.linkedin.com/in/safae-el-hamri-19134b387) · [GitHub](https://github.com/Safae-ElHamri)
