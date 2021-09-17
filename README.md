## weather-application
weather application using Vanilla JavaScript and openweathermap api 

## Open source api openweathermap.org 
- Try creating a account with openweathermap.org
- once sign in try navigating to Api Key section
- You will find a series of number similar to this `2u9e292u98u839y88938938`
- try copying the number and paste it in your application

## Replacing your api key 

```javascript
const API-KEY = '2u9e292u98u839y88938938';
// replace the api key with the key you copied from openweathermap.org 
```
## Calling API by geographical coordinates- latitude and longitude

```javascript
    const API = `api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API-KEY}`
```

## Calling API by city ID

```javascript
    const API = `api.openweathermap.org/data/2.5/weather?id=${city-id}&appid=${API key}`
```