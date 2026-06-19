# Random AI Game

A beginner-friendly one-file JavaScript Canvas platform fighter prototype.

## Game

This is now a scrolling 2D platformer fighting game prototype with enemy waves, regeneration, respawning, a bigger map, a boss transition, and a boss special that starts an inside-battle beam clash minigame.

### Controls

- **A**: Move left
- **D**: Move right
- **W**: Jump
- **J**: Melee attack
- **K**: Ranged attack
- **K during beam clash**: Mash to push the beam back

## Features

- One player character represented by a colored rectangle
- Side-scrolling platformer camera
- Bigger map with many platforms
- Multiple enemies with different types: normal, fast, and tank
- Enemy fighting AI that can chase, jump, melee, and shoot
- Slow constant player regeneration
- Slow constant enemy and boss regeneration
- Player health, lives, respawn timer, and respawn shield
- Ranged projectile attack with **K**
- Melee attack with **J**
- Boss battle after reaching the far side or surviving long enough
- Boss melee, boss projectile, and boss special attack
- Boss special cutscene into an inside-battle beam clash
- Win/lose states and restart button

## How to play locally

Download or clone the repo, then open `index.html` in a browser.

## Beginner editing ideas

Inside `index.html`, try changing:

- World width: `width: 3800`
- Player speed: `speed: 1.18`
- Player max speed: `maxSpeed: 8.5`
- Player health: `health: 110`
- Number of lives: `lives: 3`
- Enemy list: the `spawnEnemies()` function
- Boss health: `health: 450`
- Boss special cooldown: `specialCooldown: 260`
- Beam clash duration: `clashTimer = 360`
- Platform positions: the `platforms` array
