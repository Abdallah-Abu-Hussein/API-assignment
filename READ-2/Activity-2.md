## Investigate appropriate APIs for the City Explorer System, you need to explain the following for each API that will be used

## **In the city explorer project, we used three APIs :**

* LocationIQ
* weatherbit
* themoviedb




## **LocationIQ**

![](https://avatars.githubusercontent.com/u/41891924?s=280&v=4)

### API Description

LocationIQ offers enterprise-grade location-based solutions that are adaptable. Every day, we collaborate with developers, entrepreneurs, and businesses all across the world to serve billions of requests. This page will provide you an overview of our API's technical elements and will assist you in getting started.
### API Usage

In Our App the user can type the city name in the search bar , and throw the API we wil return the latitude and longtitude for chosen city with an map in form of Image.

### API Endpoints/Request URLs
<https://city-explorers.herokuapp.com/getWeather?city>=<anycity>

or you can use the local host...

### Authentication Key

REACT_APP_LocationIQ_Key : pk.343f1f863b04b629c9c89f7f0307d91c

## **weatherbit**

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHaO3pn0fIFzmPScN2boxDRMH8BIbxZUCC3APXdo2RpvYLiTKUMCD4zBqx8EMoz7Mno78&usqp=CAU)

### API Description

You may get current weather observations from over 47,000 live weather stations, as well as historical weather data for the past 10 years, using our Weather API. In addition, utilizing the world's most reliable weather models, extremely localized weather forecasts for any place on the planet are available.
### API Usage

in Our APP we were able to use this API to know the weather for next 16 days in a chosen city.

### API Endpoints/Request URLs
<https://city-explorers.herokuapp.com/getWeather?city>=<anycity> 

or you can use the local host...
NOTE : location data and waether data will be inculded togther 
### Authentication Key
55201e1542814a65b0f2747dd99e98a8

## **Themoviedb**

![](https://www.themoviedb.org/assets/2/v4/logos/v2/blue_square_2-d537fb228cf3ded904ef09b136fe3fec72548ebc1fea3fbbd1ad9e36364db38b.svg)
### API Description
The API service is for developers that want to use our movie, TV show, or actor pictures and/or data in their apps. Our API is a mechanism that allows you and your team to retrieve and use our data and/or photos programmatically.
### API Usage

In OUR app when type the city name we will generate a list of info of movies realted to that city, like new york will give you back list of movies abot new york and so on....

### API Endpoints/Request URLs
<https://city-explorers.herokuapp.com/getMovie?city>=<anycity> 

or the localhost 

### Authentication Key

f5c9574c61c7cf6775dadf2f4ef7c960


## **sources For Activity Two :**

1. https://www.themoviedb.org/talk/615191df1c635b0044708e89#615191df1c635b0044708e8c
2. https://locationiq.com/docs
3. https://www.weatherbit.io/account/dashboard