this fetch url -->  can be accessed on wesite itself.
and there ar many way to call this API.

api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
api.openweathermap.org/data/2.5/weather?q={city name},{state code}&appid={API key}
api.openweathermap.org/data/2.5/weather?q={city name},{state code},{country code}&appid={API key}

to use the rainy img you can adjust that in nested condition: weather.weather.main === 'cloud' ? ...