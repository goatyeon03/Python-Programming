# 🌊 Underwater Treasure Hunt Game  
*A 3D Python game developed with the Ursina engine*

---

## 📖 Overview  
**Underwater Treasure Hunt** is a 3D adventure game where players explore the ocean, defend against alien creatures, and search for hidden treasures.  
The project was created as a **final assignment** for a university Python Programming course, showcasing the use of Python for interactive 3D game development.

---

## 🎯 Objective  
The goal of this project was to design a **complete interactive 3D game** using Python’s Ursina engine.  
We aimed to create a visually immersive game that demonstrates Python’s capability in 3D graphics, event handling, and animation.

---

## 🧱 Why Ursina?  
[Ursina Engine](https://www.ursinaengine.org/) is a Python-based 3D game engine that simplifies building interactive environments.

**Key Advantages**
- 💡 Open-source and beginner-friendly  
- 🧩 Object management via the `Entity` class (position, model, texture, behavior, etc.)  
- 🪄 Built-in UI system (buttons, menus, text)  
- 🎞️ Integrated animation and event system  

---

## ⚙️ Game Structure  

### 🏠 Main Menu  
When the game starts, players can:  
- Click **“Game Description (게임설명)”** to view instructions  
- Click **“Start Game (게임시작)”** to begin

### 🎮 Game Rounds  
| Round | Description |
|-------|--------------|
| **Round 0 – Monster Defense** | Defend yourself by **shooting alien monsters** approaching you using **left-click**. |
| **Round 1 – Treasure Discovery** | **Destroy blocks** by left-clicking to uncover hidden treasure boxes. |
| **Round 2 – Moving Treasure Hunt** | **Click on moving treasures** to collect them before they disappear. |
| **Round 3 – Race Against Monsters** | Compete with **fast-moving monsters** to reach the treasure first — if they get there before you, the game ends. |

---

## 🧠 Implementation Details  

### 1. Screen & UI Setup  
- Main menu with interactive buttons  
- Functions bound to each button event (start, quit, show rules)  

### 2. Object Creation  
- **Player:** controllable entity with shooting capability  
- **Monster:** custom-made 3D model created using **Blender**, with movement and collision logic  
- **Treasure:** dynamic and animated object with motion patterns  

### 3. Map & Visual Design  
- **Theme:** Deep-sea environment filled with alien creatures and hidden treasures  
- **Lighting:** Dark blue water and brown seabed to simulate underwater atmosphere  
- **Objects:**  
  - Brick-like monsters evoke tension  
  - Gold treasure chests glow in the dark  
  - Green coral blocks add environmental depth  

---

## 🧩 Technical Stack  
| Category | Technology |
|-----------|-------------|
| **Language** | Python 3.x |
| **Engine** | Ursina Game Engine |
| **3D Modeling** | Blender |
| **Additional Libraries** | Pygame (sound), Numpy, built-in Python modules |

---

## ▶️ How to Run  

1. **Clone this repository**
   ```bash
   git clone https://github.com/goatyeon03/Python-Programming.git
   cd Python-Programming
2. **Install Dependancy**
   ```bash
   pip install ursina pygame
3. **Run the Game**
   ```bash
   python UnderwaterHunterGame.py
