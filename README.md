![](logo.png)
WeatherDan v1.0

By Daniel Demby
heliomass@gmail.com
http://heliomass.com

A simple script to display the current weather for your location.


To install:

git clone git://github.com/heliomass/WeatherDan.git


To see the full range of commands:

weather_dan --help


Display the weather in Montréal:

weather_dan --woeid 3534 --display_weather
☁


Display the temperature in London in Centigrade:

weather_dan --woeid 44418 --display_temperature
5


Display the complete weather and temperature in Fahrenheit in New York City:

weather_dan --woeid 2459115 --display_weather --display_temperature --display_temperature_unit --temperature_scale f
☾ 40°F


Get the woeid for your city from:
http://isithackday.com/geoplanet-explorer
