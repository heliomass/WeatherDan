# Weather Dan

![](logo.png)

A simple script to display the current weather for your location.

## Setup
To install:

```shell
git clone git://github.com/heliomass/WeatherDan.git
```

To see the full range of commands:

```shell
weather_dan --help
```

Display the weather in Montréal:

```shell
$ weather_dan --woeid 3534 --display_weather
☁
```

Display the temperature in London in Centigrade:

```shell
$ weather_dan --woeid 44418 --display_temperature
5
```

Display the complete weather and temperature in Fahrenheit in New York City:

```shell
$ weather_dan --woeid 2459115 --display_weather --display_temperature --display_temperature_unit --temperature_scale f
☾ 40°F
```

Get the woeid for your city [here](http://isithackday.com/geoplanet-explorer)
