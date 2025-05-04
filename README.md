# Snake-Game-using-Raylib
🐍 Snake Game – Raylib Edition
A fun and customizable Snake game built using C++ and Raylib library, featuring sound effects, randomized spawn logic, and high score tracking!

🎮 Features
Classic Snake gameplay

Random food and snake spawn logic

Sound effects for eating and crashing

High score persistence via highscore.txt

Smooth animations and intuitive controls

Clean object-oriented design using classes

🛠 Requirements
C++ compiler (e.g. MinGW / g++)

Raylib library (pre-compiled or from source)

highscore.txt (auto-created if not present)

Audio files:

Sounds/eat.mp3

Sounds/wall.mp3

🚀 How to Run
Windows (assuming you have Raylib set up):
Clone or download this repository.

Make sure the path to Raylib is correct in the #include directive:

cpp
#include "C:\raylib\raylib\src\raylib.h"
You can also link Raylib using the terminal if you're not using an IDE.

Compile:

bash
g++ main.cpp -o SnakeGame -lraylib -lopengl32 -lgdi32 -lwinmm
Run:

bash
./SnakeGame
Folder Structure
bash
/SnakeGame/
│
├── main.cpp
├── highscore.txt         # Automatically created
├── Sounds/
│   ├── eat.mp3
│   └── wall.mp3
└── README.md
🎮 Controls
Key	Action
Arrow Keys	Move Snake
R	Restart Game
ESC	Quit

📁 File Overview
File	Description
main.cpp	Core game logic and class definitions
highscore.txt	Stores the best score achieved
Sounds/	Contains sound files for feedback

📌 Notes
Make sure you’ve initialized Raylib properly on your system.

If sounds don’t play, check your audio file paths or device configuration.

🧑‍💻 Contributors
Naveed Iqbal 
CT-22051
