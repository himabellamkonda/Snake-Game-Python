# Snake-Game-Python
# 🐍 Python Snake Game (Tkinter)

A sleek, classic Snake game built with Python's built-in **Tkinter** library. This project focuses on object-oriented programming (OOP), coordinate-based movement, and collision detection logic.

## 🚀 Features
* **Dynamic Scoring:** Track your score in real-time as the snake grows.
* **Collision Logic:** Game over triggers if the snake hits the wall or its own tail.
* **Smooth Controls:** Uses keyboard arrow keys for responsive movement.
* **Customizable Settings:** Easily change game speed, colors, and window size in the code.

## 🛠️ How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/himabellamkonda/Snake-Game-Python.git](https://github.com/himabellamkonda/Snake-Game-Python.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd Snake-Game-Python
    ```
3.  **Run the game:**
    ```bash
    python snake_game.py
    ```
    *(Note: Ensure you have Python installed. No external libraries like Pygame are required as it uses Tkinter!)*

## 🎮 Controls
* **Up Arrow:** Move Up
* **Down Arrow:** Move Down
* **Left Arrow:** Move Left
* **Right Arrow:** Move Right

## 📝 Project Structure
* `Snake` Class: Manages the snake's body coordinates and rendering.
* `Food` Class: Handles the randomized spawning of food items.
* `next_turn` Function: The core game loop that updates movement and checks for collisions.
