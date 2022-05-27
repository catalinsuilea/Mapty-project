# Mapty-project
Keep evidence of your workouts with this awesome Mapty app.


In this app,the user is able to mark its workouts on a map depending on its own location.

The user will complete the form,press enter and the workout will be displayed on map based on the location where he clicked on the map.

The app was created with OOP JavaScript.

First of all,we have a class App which contains all the methods and proprieties for the app's arhitecture(get location,display the map on the UI based on the current location ( for that I used Leaflet API),creating a new workout and much more)

Second,the classes for running and cycling workouts.Here ,we've got a parent class called 'Workouts' and 2 children classes(running class and cycling class) which inherit from Workouts Class.

The Cycling and Running classes were created to store the data from the form,then display it into the DOM

!!! This app was created from the Jonas Schmedtmann course from udemy !!! The functionalities that I've added are : deleting the current workout from the DOM and also deleting the object from localStorage + reseting the app.

This app is not mobile friendly,it was created with the purpose of learning OOP JavaScript.

I hope you'll have as much fun on this app as I had building it.See ya!
