##Clickey-Game

### Heroku Deployment
https://click-click-game.herokuapp.com/

 # Tech Overview
    React - A MVC framework
    React-Dom
    React-Scripts

# Understanding the application
I have created a memory game with React. This assignment breaks down the application's UI into components, manage component state, and respond to user events. It's purpose is for the user to click on an image, then the images are shuffled. If the user click the same image the game is reset and a message of "You guessed in correct", otherwise it the message "You guessed correctly" will display, and the score will advance by one.

# To run on local machine

    1. clone repository
    2. yarn install this in root and in Clickey-Game/client directory
    3. run models/schema.sql in your local MySQL server
    4. navigate to Clickey-Game/client and type yarn run build in CLI
    5. After build completed navigate to root and type node server.js
    6. go to localhost:NNNN in your browser

# Developer Credit
Douglas Boyce - A Full-stack web developer
Github respository: https://github.com/douglasboyce/Clickey-Game

![Click-Game](/images/screen-shot.png)