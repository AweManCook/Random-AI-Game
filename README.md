# Random AI Game

A beginner-friendly one-file JavaScript Canvas platform fighter prototype.

## Game

This is now a scrolling 2D platformer fighting game prototype with enemy waves, regeneration, respawning, a bigger map, a boss transition, a boss special inside-battle beam clash, and a player ability selection screen.

### Controls

- **A**: Move left
- **D**: Move right
- **W**: Jump
- **J**: Main melee attack
- **U**: Alternate melee ability
- **Tap K**: Ranged projectile
- **Hold K**: Ranged beam variant
- **K during beam clash**: Mash to push the beam back
- **1 / 2 / 3**: Choose ability set on the selection screen
- **Enter**: Start after choosing an ability set

## Ability sets

### 1. Basic Fighter

Balanced slash, quick projectile, and steady beam.

### 2. Burst Striker

More aggressive close-range damage and a wider beam.

### 3. Control Caster

Safer range, wider control tools, and a thinner piercing-style beam.

## Features

- One player character represented by a colored rectangle
- Ability selection screen before the level starts
- Side-scrolling platformer camera
- Bigger map with many platforms
- Multiple enemies with different types: normal, fast, and tank
- Enemies now have less health than before
- Enemy fighting AI that can chase, jump, melee, and shoot
- Stronger constant player regeneration
- Slower enemy and boss regeneration
- Player health, lives, respawn timer, respawn shield, and energy bar
- Main melee attack with **J**
- Alternate melee ability with **U**
- Ranged projectile with **tap K**
- Connected ranged beam variant with **hold K**
- Visual beam effect with glow, core, particles, and screen shake
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
- Player health: `health: 125`
- Number of lives: `lives: 3`
- Enemy health: the `health` values inside `makeEnemy()`
- Enemy list: the `spawnEnemies()` function
- Boss health: `health: 360`
- Beam settings: the `abilitySets` object
- Boss special cooldown: `specialCooldown: 260`
- Beam clash duration: `clashTimer = 360`
- Platform positions: the `platforms` array
