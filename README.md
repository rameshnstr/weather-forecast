## Weather Forecast

This is an API wrapper for openweathermap.org which provides access to weather data. It shows the five day weather forecast details. Enter the city name in the text box and search it, the five day weather report will be displayed.

## The returned data contains elements such as:

* City
* Co-ordinates (lat & long)
* Country
* Temperature (min & max)
* Time
* Humidity
* Weather Features

## Features

* Simple access to weather data
* By default the data is cached for 1 hour
* No adverts
* To use the API you need to sign up for API access on Open Weather Map.

#Usage

You will need to obtain an API id from Open Weather Map in order to use their Weather API. Replace the string API_KEY_HERE towards the bottom of index.html with your API key.

#JSON Response
```
{"city":{"id":1851632,"name":"Shuzenji",
"coord":{"lon":138.933334,"lat":34.966671},
"country":"JP",
"cod":"200",
"message":0.0045,
"cnt":38,
"list":[{
        "dt":1406106000,
        "main":{
            "temp":298.77,
            "temp_min":298.77,
            "temp_max":298.774,
            "pressure":1005.93,
            "sea_level":1018.18,
            "grnd_level":1005.93,
            "humidity":87
            "temp_kf":0.26},
        "weather":[{"id":804,"main":"Clouds","description":"overcast clouds","icon":"04d"}],
        "clouds":{"all":88},
        "wind":{"speed":5.71,"deg":229.501},
        "sys":{"pod":"d"},
        "dt_txt":"2014-07-23 09:00:00"}
        ]}
  ```
