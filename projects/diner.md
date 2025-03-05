---
layout: project
type: project
image: dinerfinder.jpg
date: 2024
published: true
labels:
  - iOS Application
summary: "An iOS application to help you find your next favorite diner."
---

## Diner-Finder

A lot of people, myself included, often have trouble deciding on a place to eat. We simply have so many options to choose from these days. Diner-Finder aims to help solve that problem, providing a random restaurant choice near you, fitting your own preferences and requirements. My goal with Diner-Finder was to encourage exploration and trying new things, while solving a personal problem I frequently find myself facing.

## Features
The core functionality of Diner-Finder is as follows:
* Customizable search filters for distance, budget, # of people, ratings, and dietary restrictions
* Image carousel to preview the restaurant
* Detailed information including the address, hours, ratings, and distance
* Interactive map powered by Apple's MapKit framework, with a path from your current location to the restaurant

## Development
During the development of Diner-Finder, I learned a lot about working with Apple's MapKit framework. I decided to use this in lieu of Google Maps for better performance and a native solution. The entire app is written in Swift and SwiftUI. One of the biggest challenges was maintaining a clean interface, while still having enough useful parameters and information displayed for the user. When users are already overwhelmed by choices around them, I wanted to ensure they don't feel overwhelmed by the app. After all, Diner-Finder is supposed to be the solution, rather than an additional frustration. Working with real-time data was another challenge, since the restaurant depends entirely on the user's current location, and all the respective information needs to be found afterwards. I got comfortable making API calls in Swift, which will definitely come in handy. Overall, I had a lot of fun building Diner-Finder, and learned many new concepts -- both technical and in user experience.

<div class="text-center p-4">
  <img width="300px" style="border: 3px solid black;" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/dinerfinder1.jpg?raw=true">
  <img width="300px" style="border: 3px solid black;" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/dinerfinder2.jpg?raw=true" >
  <img width="300px" style="border: 3px solid black;"  src="https://github.com/kyesteele/kyesteele.github.io/blob/main/dinerfinder3.jpg?raw=true" >
</div>
