# Pixel
[![Build Status](https://travis-ci.org/brandonasuncion/Pixel.svg?branch=master)](https://travis-ci.org/brandonasuncion/Pixel)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/df68113b2b3249708caff6601de9a665)](https://www.codacy.com/app/brandonasuncion/Pixel?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=brandonasuncion/Pixel&amp;utm_campaign=Badge_Grade)
[![npm (scoped)](https://img.shields.io/npm/v/@cycle/core.svg)]()
[![Hex.pm](https://img.shields.io/hexpm/l/plug.svg)]()

Pixel is a real-time collaborative canvas inspired off of Reddit's Place. It uses the EaselJS JavaScript library to interact with an HTML5 canvas element, and uses NodeJS as a backend to store pixel data.

Though, unlike Reddit Place, everything is anonymous. However, it can be configured to set a rate limit for each IP address.

Try it out yourself! A [live demo](http://pixel.brandonasuncion.tech/) is available!

### Dependencies
* [Node.js](https://nodejs.org/en/)
* [EaselJS](http://www.createjs.com/easeljs)
* [toastr](https://github.com/CodeSeven/toastr)
* [jQuery](https://jquery.com/)

## General Setup / Running

### Setup
1. Modify src/public/scripts/main.js to point to your public address.
	```
	var PIXEL_SERVER = 'ws://127.0.0.1:3001';
	```
2. Install the node module.
	```
	$ npm install
	```
	
### Running
1. Run the WebSocket server.
	```
	$ npm start
	```
2. Upload the `src/public/` folder to your webserver of choice.

## Usage
1. Press a number between 1-9 to select a color, or 0 to erase.
2. Click on a pixel.

## Credits
Brandon Asuncion <me@brandonasuncion.tech>

## Acknowlegements
[Reddit Place](https://redditblog.com/2017/04/13/how-we-built-rplace/)

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)