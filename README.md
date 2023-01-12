# Weather-Application-using-Go
Simple Weather Application made using Go Language
<p align-"center">Weather Project using OpenWeatherAPI</p>


This project will be getting the realtime weather details on any city in the world. We will be only using the temperature details that would be obtained using the API from openweather.

Modules used in the program are
1. "encoding/json"
2. "io/ioutil"
3. "net/http"
4. "strings"

1. We defined a struct for obtaining the API key from the apiConfig file 

2. Second struct will be for formatting or serializing our weather data that we will be getting from the API, and initializing the format for the same

3. We will be initialzing a function that would be getting the API key from the file where it's stored.

4. In main function, 
	We will be having two routes,
	One for the verifying if the connection has been established, and another function will handle the weather data
	    We need to have the name of the city for that we will be creating a function, for getting access to the string.
	We would be using ResponseWriter for getting the string out from the user
	Using the string module's spliltN fucntion we will get the string and then we would store it in a variable

5. The other two functions the hello for ensuring that the connection has been established and the query file that is responsible for bring in the data from the openWeather API service