# Deep_Sea_Defender_Game

## Description
This is an engaging and dynamic 2D side-scrolling shooter game developed using HTML5 Canvas and JavaScript. In this game, the player controls a character that moves vertically and shoots projectiles to defeat various enemies. The game's objective is to survive and achieve the highest score possible within a set time limit.

## Gameplay

### Player
- **Character**: The player controls a character that can move up and down.
- **Controls**:

  | Key        | Action                |
  |------------|-----------------------|
  | 🔼 Arrow Up   | Move the player up    |
  | 🔽 Arrow Down | Move the player down  |
  | Space      | Shoot a projectile    |
  | D          | Toggle debug mode     |

- **Abilities**:
  - The player can shoot projectiles to destroy enemies.
  - Collect power-ups for enhanced abilities.

### Enemies
The game features several types of enemies, each with unique characteristics and behaviors:
| Enemy       | Description                                                                            |
|-------------|----------------------------------------------------------------------------------------|
| Angler1     | Moves horizontally with moderate speed and takes 5 hits to destroy.                    |
| Angler2     | Similar to Angler1 but slightly stronger, taking 6 hits to destroy.                    |
| LuckyFish   | A rare enemy that, when defeated, grants a power-up to the player. It takes 5 hits to destroy. |
| HiveWhale   | A large, powerful enemy that releases drones upon defeat. It takes 20 hits to destroy. |
| Drone       | Fast-moving enemies released by HiveWhales. They take 15 hits to destroy.              |

## Rules
- **Scoring**: Points are awarded for defeating enemies. The game ends when the time limit is reached or the player's score falls below zero.
- **Power-Ups**: Collect power-ups from LuckyFish to gain temporary enhancements.
- **Ammo**: The player has a limited amount of ammo that replenishes over time.
- **Collision**: If an enemy collides with the player, the player loses points and the enemy is destroyed.

## How to Play
1. To run the game locally, simply clone the repository, navigate to the project directory, and open `index.html` in your web browser.
2. Use the `Arrow Up` and `Arrow Down` keys to move the player.
3. Press the `Space` key to shoot projectiles at enemies.
4. Avoid enemy collisions and defeat as many enemies as possible to achieve a high score.
5. Collect power-ups to gain advantages and survive longer.

---

Enjoy playing the game and aim for the highest score!

