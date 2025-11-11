🌊 Underwater Treasure Hunt Game

A 3D Python game developed with the Ursina engine

📖 Overview

Underwater Treasure Hunt is a 3D adventure game where players explore the ocean, defend against alien creatures, and search for hidden treasures.
The game was developed as a final project for a university Python Programming course, aiming to combine creativity, 3D modeling, and Python’s game development capabilities.

🎯 Objective

Our main goal was to design a complete interactive 3D game using Python — featuring multiple rounds, player controls, and original 3D models.
We wanted to deliver a game that is visually immersive and showcases the potential of Python beyond traditional data processing or simple GUIs.

🧱 Why Ursina?

Ursina Engine
 is a Python-based 3D game engine that makes it easy to build interactive worlds with minimal setup.

Advantages of Ursina:

💡 Open-source and easy to use

🧩 Object management through the Entity class (position, model, texture, behavior)

🪄 Built-in UI system (buttons, menus, text)

🎞️ Built-in animation and event handling support

⚙️ Game Structure
🏠 Main Menu

When the game launches, the player can:

Click “Game Description (게임설명)” for instructions

Click “Start Game (게임시작)” to begin

🎮 Game Rounds
Round	Description
Round 0 – Monster Defense	Defend yourself by shooting alien monsters approaching you. Use the left mouse button to fire.
Round 1 – Treasure Discovery	Destroy blocks using left-click to uncover hidden treasure boxes.
Round 2 – Moving Treasure Hunt	Click on moving treasures to collect them before they disappear.
Round 3 – Race Against Monsters	Compete against fast-moving monsters to grab the treasure first — if they reach it before you, the game ends.
🧠 Implementation Details
1. Screen & UI Setup

Start screen with clickable buttons for Play and Exit

Functions bound to button events for easy navigation

2. Object Creation

Player: controllable camera-based entity with shooting logic

Monster: custom-made 3D model created using Blender, includes movement and collision detection

Treasure: animated entity with dynamic movement patterns

3. Map & Visual Design

Theme: Deep ocean environment with alien life and mysterious treasures

Lighting: Dark blue surroundings to simulate underwater atmosphere

Objects:

Monsters appear as large brick-like aliens to evoke tension

Treasure chests are golden and glowing

Green coral blocks enhance realism and visibility

🧩 Technical Stack
Category	Technology
Language	Python 3.x
Engine	Ursina Game Engine
Modeling Tool	Blender
Additional Libraries	Pygame (sound), Numpy, Built-in Python modules
▶️ How to Run

Clone this repository

git clone https://github.com/goatyeon03/Python-Programming.git
cd Python-Programming


Install required libraries

pip install ursina pygame


Run the game

python UnderwaterHunterGame.py


Controls

🖱️ Left-click → Shoot / Break / Collect

🕹️ Follow on-screen prompts per round

🎬 Demo Video

🎥 Watch the gameplay demo:
https://youtu.be/pcVAVKuBXPY

👩‍💻 Developers

Yang Soyeon (22102326)

Lee Jihyang (23101943)

💬 Acknowledgments

We would like to thank the Ursina community for documentation and examples, and our instructor for guidance throughout this project.
