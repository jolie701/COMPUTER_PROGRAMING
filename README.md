# 2-Player Snake Game

A classic arcade-style Snake Game designed for two players, implemented as part of the Computer Programming course assignments. Players compete on the same keyboard to grow their snakes by eating food while avoiding collisions.

---

## Features
* **Dual-Player Mode:** Two players can play simultaneously on a single keyboard with independent controls.
* **Collision Detection:** Includes checks for wall collisions, self-collisions, and head-to-body collisions with the opponent.
* **Score Tracking:** Real-time scoring based on the number of food items consumed by each player.
* **Dynamic Gameplay:** Smooth game loop handling movement, rendering, and state updates.

---

## Game Controls

| Player | Movement (Up / Down / Left / Right) |
| :--- | :--- |
| **Player 1** | W / S / A / D |
| **Player 2** | ↑ / ↓ / ← / → (Arrow Keys) |

*Note: Keybindings can be customized within the source code.*

---

## How to Run

### Prerequisites
* A C/C++ compiler (e.g., GCC, Clang, or an IDE such as Code::Blocks / Dev-C++)
* Standard terminal/console environment

### Compilation and Execution
Clone the repository or download the source files, then execute the following commands in the terminal:

```bash
# Compile the code (Example using g++)
g++ main.cpp -o snake_game

# Run the game
./snake_game
