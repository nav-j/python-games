## Move the Square (Pygame)

This is a simple **Pygame project** where you can move a green square around the screen using the **arrow keys**.

---

## 🚀 Features
- A window of size **800x600** pixels.
- A **green square (60x60)** drawn on a black background.
- Move the square using:
  - ⬅️ Left Arrow → Move left
  - ➡️ Right Arrow → Move right
  - ⬆️ Up Arrow → Move up
  - ⬇️ Down Arrow → Move down

---

## Requirements
- Python 3.x  
- [Pygame](https://www.pygame.org/news)

Install pygame with:
```bash
pip install pygame
````

---

## How to Run

1. Save the code in a file, e.g., `move_square.py`.
2. Run the program:

   ```bash
   python move_square.py
   ```
3. Use the arrow keys to move the square inside the window.
4. Press the **X button** on the window to quit.

---

## 📸 Demo

* Black screen with a movable **green square** controlled by arrow keys.

---

## 📝 Code Overview

* `pygame.init()` → Initializes Pygame.
* `pygame.display.set_mode((800, 600))` → Creates a game window.
* Event loop listens for **QUIT** event to close the window.
* `pygame.key.get_pressed()` → Detects arrow key presses.
* Square drawn using `pygame.draw.rect()`.

---
