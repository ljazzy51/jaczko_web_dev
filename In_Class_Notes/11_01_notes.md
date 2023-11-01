# In Classs Notes 11/01/2023

- Document dot gives access to the html file but window and navigator also allow for the whole browser access and thinkgs like geolocation
    - navigator.geolocation is going into the navigator and grabbing the geolocation object
- Google has a dveloper platform for maps and it allows you to create an API key and create maps with the geolocation of the user 
- document.addEventListener("DOMContentLoaded", getLocation); 
    - get location doesnt need parenthesis because its not being defined its simply being passed as a reference
    - If you want to pass multiple functions you should use an anonymous function that will wrap all of your other functions that you want to 
    run when all of the content is loaded
- getCurrentPosition requires a callback function for it to log the information into so that you can use the material