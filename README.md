![cf](https://i.imgur.com/7v5ASc8.png) Lab26 - Intro to Angular and Webpack
======

## To Submit this Assignment
  * create a fork of this repository
  * write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-brian`
  * push to your repository
  * submit a pull request to this repository
  * submit a link to your PR in canvas
  * write a question and observation on canvas

## Include
* `.eslintrc`
* `.gitignore`
  * **ignore the build directory**
* `package.json`
  * create an npm `watch` script for running `webpack-dev-server --inline --hot`
* `webpack.config.js`
* `.babelrc`
* `karma.conf.js`
* `app/entry.js` -- core application logic
* `app/index.html` -- application markup
* `app/base.scss` -- must be required in at top of entry.js

## Description
* Dont use yesterdays project! Start over from scrtatch :)
* Create a cowsay application with same criteria as today's lecture demo:
* Create an **app/index.html** file that contains your HTML markup
  * *hint:* be sure to include the `ng-app` directive to point to your default angular module
* Setup an angular module and create a component for your application logic
* Your component should require in a template from **app/cowsay.html** that has an input and an pre tag for displaying cowsay's ascii art
 * the cowsay ascii art's speach bubble should be setup with two way data binding to the input
* You component should setup a controller that handles the state and logic for your cowsay template

# Testing 
* Test the inital state of your cowsay component's controller
* Test the methods of your cowsay component's controller

# Documentation
* In your README.md write a description of what angular `modules`, `components` and `controllers` are for

## Bonus
* Write CSS to make your cowsay app look like the wireframe
