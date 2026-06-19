# Random AI Game

A beginner-friendly one-file JavaScript Canvas platform fighter prototype.

## Game

This is now a scrolling 2D platformer fighting game prototype with unique character builds, enemy waves, regeneration, an NPC/key objective, a locked boss door, a boss transition, and a boss special inside-battle beam clash.

## Main objective

1. Defeat at least **3 enemies**.
2. Find the **Guide NPC** halfway through the map.
3. Press **E** near the NPC to get the key.
4. Defeat **all remaining enemies**.
5. Go to the end door.
6. Press **E** to unlock the door and enter the boss fight.

The key cannot open the door until every enemy is defeated.

### Controls

- **A**: Move left
- **D**: Move right
- **W**: Jump
- **J**: Main melee attack
- **U**: Special/alternate melee ability
- **Tap K**: Ranged projectile
- **Hold K**: Ranged beam variant
- **E**: Talk to NPC / open door
- **K during beam clash**: Mash to push the beam back
- **1 / 2 / 3**: Choose ability set on the selection screen
- **Enter**: Start after choosing an ability set

## Ability sets

### 1. Basic Fighter

- **J**: Forward Slash
- **U**: Surround Burst
- **Tap K**: Blue Bolt
- **Hold K**: Balanced Beam

A balanced build with medium projectile range, medium beam width, and solid damage.

### 2. Burst Striker

- **J**: Heavy Forward Cleave
- **U**: Explosive Surround Slam
- **Tap K**: Red Bomb Shot
- **Hold K**: Wide Burst Beam

A close-range aggressive build with heavier damage, shorter projectile range, and a wide red beam.

### 3. Control Caster

- **J**: Far Puppet Stab
- **U**: Mouse Rig Snare
- **Tap K**: Twin Violet Needles
- **Hold K**: Thin Piercing Ray

A long-range build. Its **J** hitbox appears far forward from the player, and its **U** creates a rig/snare at the mouse pointer.

## Features

- Ability selection screen before the level starts
- Each build has unique color, melee shape, projectile behavior, and beam behavior
- Side-scrolling platformer camera
- Bigger map with many platforms
- Multiple enemies with different types: normal, fast, and tank
- Lower enemy health than earlier versions
- Stronger player regeneration
- NPC halfway through the map
- Key reward after 3 kills
- Locked door at the end of the level
- Door only opens if you have the key and all enemies are defeated
- Player health, lives, respawn shield, and energy bar
- Ranged projectile with **tap K**
- Connected ranged beam variant with **hold K**
- Beam effects with glow, core, particles, and screen shake
- Boss battle after the door opens
- Boss special cutscene into an inside-battle beam clash
- Win/lose states and restart button

## How to play locally

Download or clone the repo, then open `index.html` in a browser.

## Beginner editing ideas

Inside `index.html`, try changing:

- World width: `width: 3800`
- Player speed: `speed: 1.18`
- Player health: `health: 130`
- Number of lives: `lives: 3`
- Enemy health: the `health` values inside `makeEnemy()`
- Enemy list: the `spawnEnemies()` function
- NPC position: the `npc` object
- Door position: the `door` object
- Key requirement: `enemyKills >= 3`
- Boss health: `health: 360`
- Build moves and beam settings: the `abilitySets` object
- Boss special cooldown: `specialCooldown: 260`
- Beam clash duration: `clashTimer = 360`
- Platform positions: the `platforms` array
