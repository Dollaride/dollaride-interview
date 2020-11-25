# The Problem: Display directions from an API to a map

## Introduction

Approach this solution the way you would a real world problem. Use libraries where it makes sense to, and be prepared 
to explain your thought process if you do. We expect this to take less than 12 hours of actual coding time. Please submit
a working solution.

If you have any questions, please contact [hiring@dollaride.com](mailto:hiring@dollaride.com); we're happy to help. 

## How to Submit Your Response

Please submit your solution by emailing [hiring@dollaride.com](mailto:hiring@dollaride.com) a link to **one** of the following:
- A public git repository (Github is fine) that contains your code and a `README.md` that tells us how to build and run it. 

Please ensure that your submission includes everything needed to run and view your project except the Google API key (don't worry we have our own)!

## Full Description

Please write a React Native mobile application that, given a user's input, loads driving direction data from Google Map Platform 
Directions Service and displays the directions on a map. The origin should be the user's current location and the destination 
should be wherever the user would like to go. The user should be able to enter their destination in a text input.  

You may use frameworks and build tools as long as clear, simple instructions are provided for how to run them. Be ready 
to answer questions about why you chose a given approach.

For the map
- use Mapbox 
- the user's current location should be a marker with the hex code `#0490E1`
- the user's current location should be accurate and update in real-time
- the directions should be a series of polylines with the hex code `#000000`

For the text input
- the border-radius should be `35px`
- the border's hex code should be `#EEEEEE`
- the user should only be able to provide directions to valid addresses and destinations  

Bonus points
- tests

Additionally, please satisfy these requirements:

- show a loading message while loading the data, and hide this message once the data is displayed
- display an error message if the data load fails for some reason
- the user should be able to move around the map, zoom in and zoom out
