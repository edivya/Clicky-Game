# Clicky-Game

![https://clickygame9001.herokuapp.com/](https://clickygame9001.herokuapp.com/)

## Overview

This is a memory game using React.js and The application's UI is split into four components.
This app renders 12 different Disney tv show images to the screen and each image listens for click events.

## Screenshots

![Clicky-Game](https://github.com/edivya/Clicky-Game/blob/master/src/images/Screenshot.png)

The app keeps track of the user's score and the user's score increments each time an image is clicked. However, the user's score resets to 0 if they click the same image a second time. In that case, the game will automatically restart.

Every time an image is clicked, the images shuffle themselves in a random order.

## Technologies used

- React
- JSX
- ES6
- Bootstrap
- CSS

## Deploying react app to heroku

- `heroku create clickygame9001-test --buildpack mars/create-react-app`
