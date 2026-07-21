# 🎮 Pacman Game

A multiplayer **client-server implementation** of the classic **Pacman** game developed in **Python**. This project combines networking, game logic, and graphical assets to recreate the classic arcade experience with a modular architecture.

---

# 📖 Project Overview

This project implements a network-based version of **Pacman**, where the game state is managed by a dedicated server while clients handle rendering and user input.

The game includes graphical assets for Pacman in different movement states, multiple ghost characters, and a modular codebase that separates networking, game logic, and rendering.

---

# ✨ Features

- 🎮 Multiplayer Client-Server Architecture
- 🌐 Real-Time Network Communication
- 👻 Multiple Ghost Characters
- 🟡 Animated Pacman Sprites
- 🎨 PNG Graphics Support
- ⚡ Real-Time Game State Synchronization
- 🧩 Modular Code Structure
- 🖥 Cross-Platform Python Implementation

---

# 🕹 Gameplay

The objective is simple:

- Control **Pacman** through the maze.
- Collect all available dots.
- Avoid enemy ghosts.
- Stay alive as long as possible.
- Synchronize gameplay between the server and connected clients.

---

# 🌐 Client-Server Architecture

### Server

Responsible for:

- Managing the game state
- Processing player movements
- Detecting collisions
- Synchronizing connected clients
- Broadcasting updates

### Client

Responsible for:

- Rendering the game
- Handling keyboard input
- Receiving updates from the server
- Displaying sprites and animations

---

# 📂 Project Structure

```text
Pacman/
│
├── client.py              # Client application
├── server.py              # Game server
├── game_objects.py        # Game logic and entities
│
├── assets/
│   ├── green_ghost.png
│   ├── red_ghost.png
│   ├── left_baz.png
│   ├── right_baz.png
│   ├── up_baz.png
│   ├── down_baz.png
│   └── zard_basteh.png
│
└── README.md
```

---

# 🚀 Getting Started

## Requirements

- Python 3.8+
- Pygame *(if used for rendering)*
- Pillow *(optional depending on implementation)*

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Pacman.git
```

Navigate to the project:

```bash
cd Pacman
```

---

# ▶️ Running the Game

Start the server:

```bash
python server.py
```

Open another terminal and start the client:

```bash
python client.py
```

Run additional clients to connect multiple players.

---

# 🎮 Controls

| Key | Action |
|------|--------|
| ⬅ Left | Move Left |
| ➡ Right | Move Right |
| ⬆ Up | Move Up |
| ⬇ Down | Move Down |

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Core Programming Language |
| Socket Programming | Client-Server Communication |
| PNG Assets | Game Graphics |
| OOP | Modular Game Design |
| Pygame *(Optional)* | Rendering and Graphics |

---

# 🧠 Project Highlights

- Client-Server Networking
- Modular Game Architecture
- Real-Time Synchronization
- Object-Oriented Design
- Sprite-Based Animation
- Game State Management

---

# 🔮 Future Improvements

Potential future enhancements include:

- 🎵 Background music and sound effects
- 🤖 Intelligent ghost AI (A* Pathfinding)
- 🏆 Online leaderboard
- 💾 Save & Load game
- 🌍 Internet multiplayer support
- 📱 Mobile version
- 🎨 Improved animations
- ⚡ Better network optimization
- 🧪 Unit testing
- 🎮 Lobby and matchmaking system

---

# 🤝 Contributing

Contributions are welcome!

If you have ideas for improvements or find a bug, feel free to open an Issue or submit a Pull Request.

---

# 📄 License

This project was developed for educational purposes.

You are free to use, study, modify, and improve the source code for learning and non-commercial purposes.

---

# 👨‍💻 Arpourbasir

**Alireza Pourbasir**

GitHub: https://github.com/Arpourbasir

---

⭐ If you enjoyed this project, don't forget to **Star ⭐ the repository!**
