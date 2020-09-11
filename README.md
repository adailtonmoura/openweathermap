# Introducion

I did not follow the design standards, it is worth remembering that this is just a test.

This is a website that, when clicking on the map, the user receives the temperature of the place.


<img src="https://github.com/adailtonmoura/openweathermap/blob/master/img.png">

# Getting start 

You need a mapbox api key and an openweathermap api key

Read their documentation to get an api keys:

MAPBOX: https://www.mapbox.com/

OPENWHEATERMAP https://openweathermap.org/

# index.html 

replace with your API keys

```
20  mapboxgl.accessToken ='yourApiKey';
```
```
33  url: `http://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${long}&lang=pt_br&appid=YOUR API KEY`,
```

# Important

  For more information, read the API's documentation
  
  # Inspired by 
  
  https://github.com/lucasmontano
  
  https://github.com/lucasmontano/openweathermap
