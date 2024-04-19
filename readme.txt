#Weather App Using HTML, CSS, Javascript, API's like Open Weather API
My Api Key is - c0640bd1c5e34ffe65ee529984b904bf
for access location vise tempture and humdity

API Call- 
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}

here change {city name} = xyz city like Pune
            {API key}  = write here our API Key code
We want tempture in celcius then Add - &units=metric in last of the URL 
Ex- 
    https://api.openweathermap.org/data/2.5/weather?q=pune&appid=c0640bd1c5e34ffe65ee529984b904bf&units=metric

Types of Units
#units  =  Units of measurement. standard, metric and imperial units are available. 