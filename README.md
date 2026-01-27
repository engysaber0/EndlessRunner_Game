# 🏃 Endless Runner Game (Unity)

An **Endless Runner 3D Game** developed using **Unity & C#**, where the player runs forward infinitely, avoids obstacles, and collects coins to increase their score.

This project demonstrates core game development concepts such as camera following, object recycling, collision detection, and game state management.

---

## 🎮 Game Features

- Infinite running environment using tile recycling
- Smooth camera follow system
- Coin collection system
- Obstacle collision & player damage
- Game Over UI handling
- Optimized tile management for performance

---

## 🛠 Technologies Used

- **Unity Engine**
- **C#**
- Object-Oriented Programming (OOP)
- Unity Physics & Colliders
- Coroutines

---

## 📂 Scripts Overview

### 📷 CameraController
- Makes the camera smoothly follow the player using a fixed offset.
- Implemented in `LateUpdate()` to ensure smooth movement.

### 🪙 Coin
- Detects player collision using `OnTriggerEnter`.
- Increases the player’s coin count.
- Uses a coroutine to hide and respawn the coin after 3 seconds.

### 🎮 GameManager
- Manages the **Game Over** state.
- Instantiates the Game Over UI when the player loses.

### 🚧 ObstacleDamage
- Detects collisions with the player.
- Applies damage when the player hits an obstacle.

### 🧱 TileManager
- Creates an **endless environment** by reusing tiles.
- Uses a queue system to recycle tiles efficiently.
- Spawns new tiles based on player position to ensure continuous gameplay.

---


