# 3D Maze Game (Ursina Engine)
This is a simple 3D first-person maze game built with Python using the Ursina game engine.
##  Game Overview
- Explore a 3D maze from a first-person view
- Collect coins placed around the maze
- Score increases by collecting coins
- Health decreases over time
- Save and load game progress
## Installation Steps
1. Install Python (if not already installed)  
   [Download Python](https://www.python.org/downloads/)
2. Install Ursina:
   ```bash
   pip install ursina
## Building Executable
  pyinstaller --onefile --add-data "maze.obj;." maze_game.py
## Controls
 Key        Action             
 
 W/A/S/D     Move               
 Mouse       Look around        
 Space       Jump               
 E           Collect coin       
 F5          Save game          
 F9          Load game          
## Assets
- `maze.obj`: 3D maze model (required for the game)

## Credits & License

- Game Engine: [Ursina](https://www.ursinaengine.org)
- Maze model: Basic OBJ model (open source)
- License: MIT (Free to use and modify)

