# Random AI Game

A beginner-friendly one-file JavaScript Canvas game prototype.

## Game

This is a simple 2D platformer fighting game prototype.

### Controls

- **A**: Move left
- **D**: Move right
- **W**: Jump
- **J**: Attack

## Features

- One player character represented by a colored rectangle
- Gravity and platform collision
- Short attack hitbox in front of the player
- Training dummy enemy with health
- Enemy damage and knockback
- Health bars
- Simple arena with a floor and two platforms
- Restart button after the enemy is defeated

## How to play locally

Download or clone the repo, then open `index.html` in a browser.

## Beginner editing ideas

Inside `index.html`, try changing:

- Player color: `color: "#2f80ed"`
- Enemy health: `health: 100`
- Attack damage: `enemy.health -= 20`
- Jump strength: `jumpPower: -14`
- Platform positions: the `platforms` array
