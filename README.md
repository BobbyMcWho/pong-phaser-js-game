# pong-phaser-js-game
A simple pong game using phaser.js

This was built in a day and a half based on a tutorial, and then extending past where the tutorial ended (added sound a basic AI).

You can view this in action at www.rmcd.io/pong-phaser-js-game .

## What works:

The game is playable.

You can control the paddle with the mouse.

The game detects collisions and scores correctly.

## What doesn't work:

The AI is pretty bad, behind the scenes an invisible ball is spawned that the computer paddle is supposed to go to, but the code needs some TLC.

The game never ends. I didn't implement any checks for score to end the game at a certain score. This would be relatively easy to do, I would just need to implement some a new text object. 

## Parting thoughts: 

This was an interesting tutorial, but I don't think the code examples they gave were properly object oriented. If I was to pursue further Phaser.Js games, I would make sure to structure the code more with more OOP principles in mind. 
