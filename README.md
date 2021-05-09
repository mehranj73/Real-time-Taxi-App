# Real-time-Taxi-App

Ride-sharing apps like Uber or Lyft rely on real-time, bi-directional communication to give users a great experience. In this project, I developed a similar real-time taxi app built on the messages that are sent between a rider and a driver. 

* The app has two user experiences: one from the perspective of the driver and the other from the rider. The users can sign up, login and log out.
* A rider selects a starting location and destination, and then the app broadcasts a trip request to all nearby drivers.
* An available driver accepts the trip and meets the rider at the pick-up address. 
* In the meantime, every move the driver makes is sent to the rider almost instantaneously and the rider can track the trip status as long as it is active.

## Technologies used

React, Django REST Framework, Django Channels, PostgreSQL, Redis, pytest, Google Maps API, JSON Web Tokens, Docker, Python, JavaScript
