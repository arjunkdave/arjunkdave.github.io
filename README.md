# 🎮 Capture Olin - Turn-Based Game

This is a pygame implementation of a two-player turn-based strategy game using the Model-View-Controller (MVC) framework. The game is designed to be played on a single computer, with each player taking simultaneous turns to strategically move their units and control buildings across the Olin College campus map.

---

## 🎯 Project Goal

The goal of **Capture Olin** was to create a two-player strategy game that is well-structured, technically challenging, and visually engaging. It explores real-time decision-making and predictive gameplay mechanics, with a heavy focus on player-to-player interaction rather than random chance. We sought out to create a game that would have a unique strategy component.

---

## ✨ Unique Features

- 🧠 **Simultaneous Turn-Based Gameplay**: Both players submit their moves, without knowing their opponent's move and then they are executed at the same time, requiring predictive strategy.
- 🎮 **Custom Input Controller**: Combines mouse/trackpad and keyboard input for intuitive gameplay.
- 🏛️ **Campus-Themed Map**: Nodes represent buildings on Olin’s campus, with connections based on real geography.
- 🔁 **Model-View-Controller Architecture**: A clean separation of concerns for better scalability and testing.

---

## Demos

> 🎥 Watch a short video demo of the game:  
[Capture Olin - Gameplay Demo](https://drive.google.com/file/d/1foizQ9pveL60IgcA24T1aSrCRpO4kmzs/view?usp=sharing)
---

## ⚙️ Getting Started

These instructions will get you up and running with a local version of the game.

### Prerequisites

- Python 3.12 or higher  
- Pygame

Install dependencies:

```bash
pip install pygame
```

---

## 🚀 Running the Game

To run the game:

```bash
python3 Game.py
```

---

## 🎮 Game Controls

- Click to select which Olin building you want to send Oliners to/from.
- Use number keys to select how many Oliners to send.
- Press `Space` to confirm and send.
- Press `Escape` to exit at any time.
- Pass the device between players every turn.

Instructions are also available on the game's start screen. 

---

## 📜 Game Rules

- The game map is a network of buildings (nodes) connected by pathways (edges).
- Each building starts as neutral or controlled by one player.
- Players simultaneously issue orders each round, and results resolve together.
- You can only send Oliners between connected buildings.
- Buildings spawn new Oliners at the start of each round:
  - 🏠 Home base always spawns 5 Oliners at the start of the game.
  - 🏢 Controlled buildings spawn one bonus Oliner.
- The player with the most Oliners in a building controls it.
- If both players have equal Oliners, the building belongs to the player last on the offensive.
- 🎯 Win by controlling the enemy's home-base while retaining control of your own.

---

## 🧪 Running PyTests

Run the tests with:

```bash
pytest
```

---


## 🔗 GitHub Page

Visit the GitHub project here:  
[https://github.com/olincollege/Turn-Based](https://github.com/olincollege/Turn-Based)

---

## 👥 About Us

Mateo - Hi, I'm Mateo! I'm a student at Olin College majoring in mechanical engineering. My professional passions span aerospace but more specifically research satellites such as small-sats. In my free time, I enjoy playing pool, soccer, and thrifting.
Liam -
Arjun - Hey, I'm a Babson Student currently cross registered at Olin College. I'm studying real estate and finance with a passion for innovation. In my free time, I like to play soccer, make art, and explore Boston. Hope you enjoyed the game!


---

## Attribution

- Built using [Python](https://www.python.org/) and [Pygame](https://www.pygame.org/news)
- Thanks to our instructors and peers for support and feedback throughout the project

---


