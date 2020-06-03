# Duckshooter VR
## About
Duckshooter VR is a simple game about shooting ducks in VR made with [three.js](https://github.com/mrdoob/three.js). This game runs in the browser, you can try it out [here](https://hajekjiri.github.io/duckshooter-vr). I've only tested it on Oculus Go and Oculus Quest so I'm not sure how/if it's going to run on other devices.

This project was a part of the CSC385 Computer Graphics course at [Union College](https://union.edu).

## Tips
* Click on the door with your trigger to enter the game room
* A short tutorial is displayed once you enter the game room
* On the right side of the game room you'll find a couple of settings you can play with
* On the left side of the game room you'll find a slider to play/reset the game (0 => reset, 1 => play)
* Even though the laser pointer becomes invisible once you start the game, it's still there and allows you to reset the game by setting the slider on the left side to 0
* A score is displayed once you shoot all of the ducks
* Changing the settings won't have any effect on the score as it's only based on the time it took you to shoot all of the ducks

## Runing locally
Clone the repository and put it up on your web server.
```
git clone https://github.com/hajekjiri/duckshooter-vr.git
```

You're all set. Navigate to `index.html` to play the game.
