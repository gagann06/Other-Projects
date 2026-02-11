# Other-Projects
These are projects for which source code cannot be shared - repository to be used for visual demonstration.

---

# Project 1: Maze Learning Robot — Tremaux Algorithm Navigation

---

A Java robot controller that autonomously learns and solves mazes using **Tremaux’s algorithm**.  
The system explores unknown environments, stores traversal history, and replays an optimised shortest path after learning.

This project demonstrates algorithmic problem solving, stateful system design, and intelligent navigation using custom data structures.

---

## Key Highlights

- Implemented **Tremaux’s maze-solving algorithm** for systematic exploration of unknown environments
- Designed custom data structures to record visited routes and analyse traversal history
- Built a learning system that computes and replays an optimised shortest path after exploration
- Engineered a modular control architecture separating exploration, backtracking, and fast-path execution
- Reduced navigation time across runs through adaptive decision-making

---

## How It Works

### Exploration Phase
- Robot explores the maze and marks visited paths
- Tracks incoming and outgoing directions at junctions
- Avoids redundant traversal using visit counts

### Learning & Optimisation
- Stores traversal data during exploration
- Identifies the best discovered route based on visit history

### Fast Path Execution
- Replays the optimised path on subsequent runs
- Minimises unnecessary movement and decision overhead

---

## Technologies

- Java
- Algorithmic pathfinding
- Custom data structures
- Object-oriented design

---

## Demo / Screenshots

Images of exploration and path optimisation will be added.


# Project 2: Backwords (TODO)

