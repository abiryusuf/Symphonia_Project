# projectSymphonia

 * Project Description: a web-based application that functions as an alarm clock     which delivers cross-referenced information from Spotify and OpenWeatherApp.org   to the user by playing a song that’s representative of the local weather. 

* User story: 

 As a young professional who has very little free time, I want an application that plays that plays songs that a) tell me the weather to save time and b) give me the mood (we have to decide on the story) so that to feel connected to nature and enjoy music in a dynamic and unique way so that I can enjoy every moment of my day.

* PseudoCode
 User sets time of alarm
 User sets location
 Alarm goes off
 App goes to weather API
 Weather API returns information based on location
 Based on information, a song will play

GIVEN User sets up time alarm
WHEN alarm goes on
THEN App goes to weather API
WHEN weather API is retrieved
THEN based on the information, Spotify API (or song from database) returns a song related to the weather
WHEN alarm goes off
THEN I´m able to set up a new alarm.

