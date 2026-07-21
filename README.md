🎮 Pacman Game
A multiplayer, console-and-graphical client-server implementation of the classic Pacman game developed in Python.  
ZIP

📖 Project Overview
This project brings the classic Pacman arcade experience into a networked environment. It features a client-server architecture where multiple game components, including various ghosts and Pacman state sprites (such as open/closed mouth variants and directional states), interact dynamically across the network.  
ZIP
+ 1

The repository is structured cleanly into server-side game logic, client-side rendering, and asset handling.  
ZIP

🎯 Features
✅ Client-Server architecture for multiplayer or remote gameplay  
ZIP

✅ Custom game object mechanics and state handling  
ZIP

✅ Graphical game sprites (Pacman directional states, green & red ghosts)  
ZIP

✅ Real-time game state synchronization  
ZIP

✅ Modular and clean project structure  
ZIP

🕹️ Game Rules
General Gameplay
The game is played on a grid-based maze featuring Pacman and multiple Ghosts.  
ZIP

Pacman navigates through the board to consume points/dots while avoiding ghosts.  
ZIP

Ghosts (e.g., Red Ghost, Green Ghost) traverse the maze attempting to catch Pacman.  
ZIP

Movement & Network Mechanics
The Server manages game state updates, object collisions, and positions.  
ZIP

The Client sends player input/movement commands to the server and renders the game assets locally.  
ZIP

Game objects update dynamically depending on movement direction and state changes.  
ZIP

📂 Project Structure
Pacman/
│
├── client.py            # Client-side script for user connection & rendering
├── server.py            # Game server logic and state manager
├── game_objects.py      # Core game entities and physics/board logic
│
├── green_ghost.png      # Green Ghost sprite asset
├── red_ghost.png        # Red Ghost sprite asset
├── left_baz.png         # Pacman moving left sprite asset
├── right_baz.png        # Pacman moving right sprite asset
└── zard_basteh.png      # Pacman closed-mouth sprite asset
  
ZIP

🚀 Getting Started
Requirements
Python 3.8 or newer

Recommended image handling libraries (e.g., Pygame or Pillow depending on client implementation)

Run the Game
Clone the repository:

Bash
git clone https://github.com/your-username/Pacman.git
Navigate into the project directory:

Bash
cd Pacman
Start the Server:

Bash
python server.py
Launch the Client (in a separate terminal window):

Bash
python client.py
🛠 Technologies Used
Technology	Purpose
Python 3	
Core programming language  
ZIP

Sockets / Networking	
Client-Server communication (server.py & client.py)  
ZIP

PNG Graphics	
Visual assets for Pacman states and ghosts  
ZIP

🔍 Future Improvements
Possible enhancements include:

Graphical User Interface improvements using Pygame or Arcade

Sound effects and background music

AI-driven ghost pathfinding algorithms (e.g., A* algorithm)

Score leaderboards and persistence

Support for multiple concurrent Pacman players

Save and reload game state functionality

Comprehensive unit tests for game physics and collisions

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Feel free to fork the repository and submit a Pull Request.

📄 License
This project is created for educational and learning purposes.

You are free to study, modify, and build upon the source code.

👨‍💻 Arpourbasir
Alireza Pourbasir

GitHub:

https://github.com/Arpourbasir

⭐ If you found this project useful, consider giving it a star!
