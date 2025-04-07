Star Wars Maze Game
This project is a maze-based game developed using Object-Oriented Programming principles and pathfinding algorithms. The game features Star Wars characters where the player must navigate through a maze while avoiding enemy characters.
Project Overview
The Star Wars Maze Game is a desktop application where players control either Luke Skywalker or Master Yoda as they navigate through a maze to reach a trophy while avoiding enemy characters (Darth Vader, Kylo Ren, and Stormtrooper). The game implements various pathfinding algorithms for enemy character movement and showcases OOP concepts through a hierarchical class structure.
Features

Character Selection: Choose between Luke Skywalker or Master Yoda, each with unique abilities
Enemy Characters: Three different enemy types with distinct abilities

Darth Vader: Can break through walls
Kylo Ren: Moves twice as fast (two squares per turn)
Stormtrooper: Standard movement (one square per turn)


Dynamic Pathfinding: Enemies use pathfinding algorithms to chase the player
Life Management: Different health management for each character

Luke Skywalker: Has 3 lives, loses 1 life when caught
Master Yoda: Has more durability, loses only half a life when caught


Interactive Maze: Navigate through a maze with obstacles
Visual Interface: Graphical representation of the game state
Audio Effects: (Bonus) Sound effects when enemies catch the player

Implementation Details
Class Structure
The game follows a hierarchical class structure based on OOP principles:

Location Class: Manages coordinate information (x, y)
Character Class: Base class for all characters with common attributes and methods
Good Characters: Luke Skywalker and Master Yoda classes
Evil Characters: Darth Vader, Kylo Ren, and Stormtrooper classes

Pathfinding Algorithms
Enemy characters use pathfinding algorithms to determine the shortest path to the player:

BFS (Breadth-First Search)
A* Algorithm
Custom pathfinding for special character abilities

Game Mechanics

The player starts at a predetermined position
Enemy characters enter from designated entry points
The player must reach the trophy while avoiding enemies
If caught, the player loses lives according to their character's abilities
Game ends when the player either reaches the trophy or loses all lives

Requirements

Programming Language:C#
UI: WPF
Desktop GUI libraries for graphical interface
Map data loaded from a text file 
