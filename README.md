# weather-react-native
A simple Weather application in React Native Expo.
---
Important to have installed on your computer
```
- NodeJs (https://nodejs.org/en/download/)
- Npm
- Expo-CLI (npm install --global expo-cli or https://docs.expo.dev/get-started/installation/)
```
Install the required dependency presented in the **package.json** file
```
npm install
```
Modify information in the **api/ConsultApi.js** file
```js
axios.get(`https://api.weatherapi.com/v1/forecast.json?key=<API_KEY>...`)
```
"API_KEY" -> Here you will need to put your KEY to access the api, create your account at [weatherapi.com](https://weatherapi.com).<br/>

---
After the change, give the command on the console to start the project
```
expo start
```
I'm going to run it in a web application, so I'm going to run
```
expo start --web
```

