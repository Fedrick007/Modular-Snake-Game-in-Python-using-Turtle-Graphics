# 🐍 Snake Game in Python (Turtle Graphics)

A classic Snake Game built using Python’s Turtle graphics module, designed with a clean and modular object-oriented architecture. The project separates game logic into multiple components for better readability, maintainability, and scalability.

---

## 🚀 Features

- Real-time snake movement using keyboard controls
- Modular and object-oriented code structure
- Random food generation
- Collision detection (walls & self)
- Persistent high score using file handling
- Smooth animation with optimized screen refresh

---

## 🧠 Project Structure
```
snake-game/
├── main.py          # Game loop and event handling
├── snake.py         # Snake movement, growth, and reset logic
├── food.py          # Food creation and random placement
├── scoreboard.py    # Score and high score management
├── data.txt         # Stores high score persistently
└── README.md
```
---

## 🧩 Module Overview

### main.py
- Initializes the game screen and settings
- Handles user input through keyboard listeners
- Runs the main game loop
- Detects collisions and resets the game state

### snake.py
- Creates and manages the snake body
- Controls movement and direction logic
- Handles snake growth when food is eaten
- Resets the snake after collisions

### food.py
- Generates food at random screen positions
- Uses Turtle inheritance for simplicity

### scoreboard.py
- Displays current score and high score
- Reads and writes high score using file I/O
- Resets score without ending the game

---

## 🎮 Controls

Up Arrow    → Move Up  
Down Arrow  → Move Down  
Left Arrow  → Turn Left  
Right Arrow → Turn Right  

---

## 🛠️ Technologies Used

- Python 3
- Turtle Graphics
- Object-Oriented Programming (OOP)
- File Handling
- Event-Driven Programming

---

## ▶️ How to Run

1. Clone the repository:
   git clone https://github.com/your-username/snake-game-python.git

2. Navigate to the project directory:
   cd snake-game-python

3. Run the game:
   python main.py

---

## 📈 Learning Outcomes

- Applied OOP concepts in a real project
- Built modular and reusable Python components
- Implemented collision detection logic
- Used file handling for persistent data storage
- Managed real-time animations using Turtle

---

## 🔮 Future Enhancements

- Difficulty levels
- Sound effects
- Pause and resume feature
- Enhanced UI and animations
- Convert to executable (.exe)

---

## 👨‍💻 Author

Fedrick Samuel W  
Software Engineer |
Python Developer | Data Science Enthusiast

---

⭐ If you find this project useful, feel free to star the repository!
