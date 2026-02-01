# 🚀 Space Dodge

A 2D arcade-style survival game built using Python and Pygame.

The player must dodge falling obstacles for as long as possible.
The game increases in difficulty over time, making survival progressively harder.

---

## 🎮 Gameplay

1. Move left and right using arrow keys
2. Avoid falling stars
3. Survive as long as possible
4. Timer tracks survival time
5. Difficulty increases dynamically

## 🧠 Concepts Used

1. Game Loop Architecture
2. Frame Rate Control (60 FPS)
3. Collision Detection using pygame.Rect
4. Event Handling
5. eyboard Input Handling
6. Dynamic Difficulty Scaling
7. Time-based Scoring
8. Safe List Mutation

## 🛠️ Tech Stack

Python 3.x

Pygame

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/space-dodge.git
```

```bash
cd space-dodge
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the game:

```bash
python main.py
```

📈 Difficulty Logic

The spawn rate increases over time:

```bash

star_add_increment = max(200, star_add_increment - 50)
```


As the increment decreases, stars spawn more frequently.

## 🎯 Learning Outcomes

- This project demonstrates understanding of:
- Real-time game loops
- Object collision logic
- Frame-based animation
- Interactive UI rendering
- Basic game balancing mechanics

## 🔮 Future Improvements

- Add restart option
- Add vertical movement
- Add scoring system based on dodges
- Add sound effects
- Refactor into classes
- Add main menu screen
