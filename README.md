# WeatherX
WeatherX is a bot I made for general training with **APIs** and data manipulation. The bot is under development, so it is not yet ready to be used. The bot was created with leveraging the [WeatherAPI](https://www.weatherapi.com/) API. These APIs have many features and in my spare time I aim to implement all of them in the bot.

## Features
- Configurable automatic message for daily weather forecast for a city, time is configurable.
- Forecast for up to **7 days**.
- Configuration of units of measure (metric or imperial).
- Aesthetically appealing, used different emoji that change automatically based on weather conditions and based on the nationality of the city.

## How it works
The only configuration the bot needs is for automatically sending daily weather forecasts. To configure the bot, just use the `/configure` command and follow the instructions. The configuration is totally interactive and simple. 

## Commands
- `/configure`: configure the automatic message for the daily weather forecast.
- `/forecast <city> <units> <days>`: shows the weather forecast for the specified city. The `units` parameter can be `metric` or `imperial`, while the `days` parameter can be a number from 1 to 7.
- `/weather <city> <units>`: shows the current weather conditions for the specified city. The `units` parameter can be `metric` or `imperial`.

## ToDo
- [ ] Add integration for historical weather
- [ ] Add integration for marine conditions.
- [ ] Add integration for atronomy
- [ ] Add integration for forecast air quality
- [ ] Add integration for weather alerts
- [ ] Add integration for bulk weather
