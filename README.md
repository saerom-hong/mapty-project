# 🗺 Mapty Project
The application asks you for your current location and displays it on the map. Once you pick the specific location on the map and put your workout information, It is displayed on the list. It's like a diary for workouts but on the map!

## Features

Users can  
- see their current location on the map
- put the marker where they want to
- record their workout based on the location and current date. 

✍️ There are two workout types that users can choose
- 🏃‍♀ **Running** <br>
 'distance', 'duration', 'cadence'
- 🚴‍ **Cycling** <br>
 'distance', 'duration', 'cadence' 

## 📽 Project Overview
<img width="1433" alt="Screen Shot 2022-01-17 at 22 13 19" src="https://user-images.githubusercontent.com/94627346/149837565-45d99e4d-d387-4d84-862a-f878b1417a28.png">


## Technologies
- Browser API (Geolocation)
- Third party library 'Leaflet'(https://leafletjs.com/)

## Things I learned
- **Architecture of the application** \
Through the project planning, I gained a clear understanding of how we build the application. Building the data structure helped to decide where and how to store the data. 
- **How to use third party library and read their document, apply their code for implementing functions** \
This is my first time to use a third party library in JS! I learned from the basic functions up to how to make it dynamic and interactive with my application. How thrilling it was! 
- **The importance of Input Validation** \
Checking input validation is an important part of creating an application that works with user input.
What if the user puts invalid data (in this case, string or negative numbers)? We should check the validation of the data before returning any function. 
- **How to work with local storage API** \
In order to make the data persist across multiple page reloads, by using local storage, I could save the data the user put so even if the user closes the page and comes back again, the previous data is still available. But be careful! We shouldn't use local storage to store large amounts of data. 
