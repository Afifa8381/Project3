
# FEND Project #3: Weather Journal
## Overview

**Weather Journal** is the third project of Udacity [Front End Web Developer] nanodegree program. 
It requires to build a single-page JavaScript app which creates a weather record for user based on their input and data from [OpenWeatherMap API].



## Features
* Local server (*server.js*) is running on ```port 3030```.
* Data is retrieved from external [OpenWeatherMap API](https://openweathermap.org/current#zip) in ```JSON``` format.
  * API calls use ```zip code``` entered by the user. Search works only for US zips.
* The following values are updated dynamically:
  * date
  * temperature
  * user input 
  

## Dependencies
Cool tech stuff used in this project:
* Node.js
  * [Official Guides for Node]
* Express framework
  * [Example of an Express server]
  * [Routing for Express]
* Node.js packages:
  * [cors]
  * [body-parser]

## Getting Started
### Prerequisites
1. Download [Node.js]
2. Install the following packages using ```npm```.
```sh
$ npm install express
$ npm install cors
$ npm install body-parser
```
### Running Locally 
To run **Weather Journal** locally:
1. Clone this repository.
2. ```cd``` into project directory.
3. Start the local server from command line.
```sh
$ node server.js
```
4. Open ```http://localhost:3030``` in your browser.
### Using Another API Key
To use your own OpenWeatherMap API key,
1. Create an account on [https://openweathermap.org/api]
2. In *app.js*, save your key in ```apiKey``` constant.
## Authors
Afifa Ali
