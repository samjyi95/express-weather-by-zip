![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# A RESTful Express Weather App

## Objectives
* Build an Express web app that includes a GET and POST request to get the location of our user, and then return data that we will use when learning about API calls to query for the weather in the users location. 
* Use a new NPM package, [Weather-JS](https://www.npmjs.com/package/weather-js).
* Declare/create x1 template for your pages to inherit from, and use in your app. 
* Use best practices when writing code and in organizing your routes. 

## Getting Started

* Fork and clone this repository.
* Make "entry point" for your app (`touch index.js`). 
* Run `npm init -y` to setup our folder. 
* Install your dependencies (Express, EJS, [Weather-JS](https://www.npmjs.com/package/weather-js)). 
* Create a `.gitignore` file 
* Run `git init` to initialize git in folder. 
* Start writing out Express app in `index.js`.

## Requirements/App Map

* Index.js file should include the following routes/views:
  - `/`: homepage that includes some instructions for the user, and a form that includes a text input and a submit button. The text input should query for a zipcode, and the form should then as a post method send the zipcode to your backend for use. This route should take both GET and POST methods. 
  - `/weather`: a results page that displays the weather in the location given by the user. Display whichever data points from your `Weather-JS` call that you find relevant/interesting. 
  - `/weather/:zipcode`: a GET route that returns the weather data for whichever zipcode the user passes to route. 

## Bonuses

* Write an if statement that passes one template if the weather is "nice" outside, and another if it is not. You get to decide what constitutes "nice" in this case!
* Write a function that queries a random zipcode for the weather, and returns the `/weather/:zipcode` route with the result. 

---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
