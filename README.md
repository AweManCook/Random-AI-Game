# Random AI Game

A beginner-friendly one-file JavaScript Canvas platform fighter prototype.

## Game

This is a simple 2D platformer fighting game prototype with melee attacks, ranged attacks, enemy AI, respawning, and a loading screen.

### Controls

- **A**: Move left
- **D**: Move right
- **W**: Jump
- **J**: Melee attack
- **K**: Ranged attack

## Features

- One player character represented by a colored rectangle
- Faster movement than the first prototype
- Gravity and platform collision
- Short melee hitbox in front of the player
- Ranged projectile attack with **K**
- Enemy training bot with health
- Enemy fighting AI that can chase, jump, melee, and shoot
- Enemy damage and knockback
- Player health, lives, respawn timer, and respawn shield
- Health bars for player and enemy
- Simple arena with a floor and two platforms
- Loading screen before each match
- Restart button after winning or losing

## How to play locally

Download or clone the repo, then open `index.html` in a browser.

## Beginner editing ideas

Inside `index.html`, try changing:

- Player speed: `speed: 1.15`
- Player max speed: `maxSpeed: 8.5`
- Enemy health: `health: 140`
- Melee damage: `enemy.health -= 22`
- Ranged damage: `damage: owner === "player" ? 14 : 10`
- Jump strength: `jumpPower: -14.5`
- Number of lives: `let playerLives = 3`
- Platform positions: the `platforms` array
