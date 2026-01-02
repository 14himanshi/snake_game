# Retro Snake Game 🐍

![Retro Snake Gameplay](screenshot.png)

A classic Snake game built with **C++** and the **Raylib** library. This project features smooth movement, collision detection, sound effects, and score tracking.

## 🚀 Features
* **Object-Oriented Design**: Clean code structure using `Snake`, `Food`, and `Game` classes.
* **Dynamic Snake Growth**: Efficiently manages the snake's body using `std::deque`.
* **Collision Detection**: Includes logic for boundary checks, self-collision, and food consumption.
* **Audio Integration**: Features real-time sound effects for eating (`eat.mp3`) and game over (`wall.mp3`).
* **Input Handling**: Implementation of responsive movement controls while preventing illegal 180-degree turns.

## 🛠️ Tech Stack
* **Language**: C++
* **Graphics Library**: [Raylib](https://www.raylib.com/)
* **Data Structures**: `std::deque` (Double-ended queue) for the snake body.

## 🎮 How to Play
1. **Objective**: Eat the food to grow and increase your score.
2. **Controls**: Use the **Arrow Keys** (Up, Down, Left, Right) to change direction.
3. **Game Over**: The game resets if you hit the boundary or collide with your own tail.

## 🔧 Installation & Setup
To run this project locally, ensure you have **Raylib** installed on your system.

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/14himanshi/snake_game.git](https://github.com/14himanshi/snake_game.git)
   cd snake_game