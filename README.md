# We've created spooky creatures

Just a circle and a triangle? That's crazy talk. You should now have a creature class (or function) that can be appended to your DOM.

<img src="https://github.com/sirMerr/spaceship-game/blob/master/src/static/Creature.svg" width=150/>

Notes: https://slides.com/tiffanyle-nguyen/intro-js

## What to do now

Let's make them move towards our ship! Same thing as for the laser, but for our creature, but with collision.

- Create a `move` function that moves the creature to the left until
  - It hits our ship
  - OR the edge of the screen
  - OR hits a laser (pew)
- Make the creature disappear if the above conditions are reached (add the `baddie-died` class and replace the `img`'s `src` with `src/static/boom.svg`

## Requirements

- Clone/Download this repository and use this branch

## Usage

Open `index.html` in the modern browser of your choosing from the downloaded/cloned repository.
