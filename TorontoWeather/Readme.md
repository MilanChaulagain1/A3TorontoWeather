# Title
Weather App

# Dependencies 
net8.0
NETStandard.Library (>= 2.0.3)
Newtonsoft.Json (>= 13.0.3)
System.Net.Http (>= 4.3.4)


# Release Notes (for this version)
This version only has Toronto weather.

# Description
This is a package for Toronto Weather App.


# How to use it
private readonly WeatherService _weatherService
await _weatherService.GetTorontoWeatherAsync() - This will fetch the weather data for Toronto.
_weatherService.ExtractMaxTemperaturesAndDays() - This will Builds a formatted string that displays each date, its day of the week,
and its corresponding maximum temperature in Celsius.



# Copyright
Milan Chaulagain