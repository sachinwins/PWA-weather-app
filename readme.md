# Progressive Web App and Gulp 4

PWA which will work in offline, lie-fi & network.
Uses service  worker, indexed DB

I wanted to share my own boilerplate for gulp 4 that I use for simple front-end websites that use HTML, SCSS, and JavaScript. And I'm using Gulp 4 to compile, prefix, and minify my files.

## Quickstart guide

* Clone or download this Git repo onto your computer.
* Install [Node.js](https://nodejs.org/en/) if you don't have it yet.
* Run `npm install`
* Run `npm run build` to build the dist folder
* Run `npm run start` to run the app on local server

In this proejct, Gulp is configured to run the following functions:

* Clean dist folder
* Compile the SCSS files to CSS
* put source map and generate source map files
* Autoprefix and minify the CSS file
* Concatenate the JS files
* Uglify the JS files
* Process images to reduce  size 
* minify index.html file
* Add cache buster
* Move final CSS, JS, images & index.html files to the `/dist` folder
* Run app on local server
* Watch for specific changes and auto reload
 