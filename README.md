# Lab Work №4: Data Analysis. Working with API, Creating a Chatbot

## Work Description
Aim of the work: To study working with API, master working with matplotlib, pandas libraries. Creating a tg-bot.

### Tasks
1. Download an arbitrary dataset and describe it.
2. Visualize the data using Matplotlib.
3. Formulate a statistical hypothesis and test it using pandas.
4. Create a telegram bot in Python that retrieves data via API (current weather, weather forecast, currency exchange rates, etc.).

## Data Description
Example data in JSON format:

```json
{
  "coord": {
    "lon": 10.99,
    "lat": 44.34
  },
  "weather": [
    {
      "id": 501,
      "main": "Rain",
      "description": "moderate rain",
      "icon": "10d"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 298.48,
    "feels_like": 298.74,
    "temp_min": 297.56,
    "temp_max": 300.05,
    "pressure": 1015,
    "humidity": 64,
    "sea_level": 1015,
    "grnd_level": 933
  },
  "visibility": 10000,
  "wind": {
    "speed": 0.62,
    "deg": 349,
    "gust": 1.18
  },
  "rain": {
    "1h": 3.16
  },
  "clouds": {
    "all": 100
  },
  "dt": 1661870592,
  "sys": {
    "type": 2,
    "id": 2075663,
    "country": "IT",
    "sunrise": 1661834187,
    "sunset": 1661882248
  },
  "timezone": 7200,
  "id": 3163858,
  "name": "Zocca",
  "cod": 200
}

```
## Statistical Hypothesis
Two hypotheses for this program:

• H0: µ = 0 (the average temperature is equal to 0)

• H1: µ ≠ 0 (the average temperature is not equal to 0)
