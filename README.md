# bom

A simple command-line weather app using the Australian Government Bureau of Meteorology's data.

Requires Pycurl!!!
```
# using Python's package manager
➜  ~ pip install pycurl     

# using your distro's package manager
➜  ~ sudo apt install python3-curl
```

## How to use

```
# Run using Python3
➜  bom git:(main) python3 weekly.py
```

This will input a list of locations BOM provides. From there, plug in your desired location and it will give your forecast!

```
➜  bom git:(main) python3 weekly.py Bondi 
Bondi Forecast:
Saturday
  forecast_icon_code: 💨 
  air_temperature_maximum: 39 Celsius
  precis: Windy. Mostly sunny. 
  probability_of_precipitation: 20% 
----------------------------------------
Sunday
  forecast_icon_code: ☁️ 
  precipitation_range: 0 to 1 mm 
  air_temperature_minimum: 21 Celsius
  air_temperature_maximum: 23 Celsius
  precis: Cloudy. 
  probability_of_precipitation: 30% 
----------------------------------------
Monday
  forecast_icon_code: 🌤 
  air_temperature_minimum: 21 Celsius
  air_temperature_maximum: 25 Celsius
  precis: Partly cloudy. 
  probability_of_precipitation: 10% 
----------------------------------------
Tuesday
  forecast_icon_code: 🌤 
  air_temperature_minimum: 21 Celsius
  air_temperature_maximum: 25 Celsius
  precis: Partly cloudy. 
  probability_of_precipitation: 10% 
----------------------------------------
Wednesday
  forecast_icon_code: 🌤 
  air_temperature_minimum: 21 Celsius
  air_temperature_maximum: 25 Celsius
  precis: Cloud clearing. 
  probability_of_precipitation: 10% 
----------------------------------------
Thursday
  forecast_icon_code: 🌤 
  precipitation_range: 0 to 1 mm 
  air_temperature_minimum: 22 Celsius
  air_temperature_maximum: 31 Celsius
  precis: Partly cloudy. 
  probability_of_precipitation: 30% 
----------------------------------------
Friday
  forecast_icon_code: 🌦 
  precipitation_range: 0 to 1 mm 
  air_temperature_minimum: 21 Celsius
  air_temperature_maximum: 25 Celsius
  precis: Shower or two. 
  probability_of_precipitation: 50% 
----------------------------------------
```

Defaults to NSW. You can update the queried XML file in the script to that of your state. http://www.bom.gov.au/catalogue/data-feeds.shtml
