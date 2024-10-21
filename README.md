# DungeonDev: Crawl & Code

## Project Overview

This project is an ambitious roguelike dungeon crawler game implemented in Python using Pygame. The game uniquely integrates LeetCode-style coding challenges, offering an entertaining way to practice programming skills while enjoying a pixel art adventure.

### Key Features

1. Procedurally generated dungeons
2. Turn-based gameplay
3. Enemy AI with pathfinding
4. Inventory and item system
5. Combat system with various mechanics
6. Pixel art graphics
7. Save/Load functionality
8. LeetCode-style coding challenges integrated into gameplay

## Learning Objectives

- Implement and optimize various data structures (graphs, priority queues, hash tables)
- Apply algorithms for procedural generation, pathfinding, and game logic
- Develop skills in object-oriented programming and design patterns
- Gain experience in game development concepts and Pygame
- Practice problem-solving skills relevant to technical interviews
- Solve coding challenges in a gamified environment

## Setup and Installation

1. Ensure you have Python 3.7+ installed on your system.
2. Clone this repository:
   ```
   git clone https://github.com/yourusername/dungeon-dev-crawl-and-code.git
   cd dungeon-dev-crawl-and-code
   ```
3. Set up a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install the required dependencies:
   ```
   pip install pygame
   ```

## Project Structure

```
dungeon-dev-crawl-and-code/
│
├── src/
│   ├── main.py
│   ├── game/
│   │   ├── __init__.py
│   │   ├── game.py
│   │   ├── player.py
│   │   ├── enemy.py
│   │   └── item.py
│   ├── world/
│   │   ├── __init__.py
│   │   ├── dungeon_generator.py
│   │   └── tile.py
│   ├── ui/
│   │   ├── __init__.py
│   │   └── user_interface.py
│   ├── utils/
│   │   ├── __init__.py
│   │   └── pathfinding.py
│   └── challenges/
│       ├── __init__.py
│       ├── challenge_manager.py
│       └── challenge_data.json
├── assets/
│   ├── sprites/
│   └── fonts/
├── tests/
├── README.md
├── requirements.txt
└── .gitignore
```

## Running the Game

To start the game, run the following command from the project root:

```
python src/main.py
```

## Development Roadmap

1. Basic game loop and player movement
2. Simple dungeon generation
3. Collision detection and wall rendering
4. Enemy placement and basic AI
5. Implement A* pathfinding for enemies
6. Add combat system
7. Develop inventory and item system
8. Implement save/load functionality
9. Enhance graphics and UI
10. Balance gameplay and add progression systems
11. Integrate LeetCode-style challenges
12. Develop visual puzzle representations of coding problems
13. Implement challenge reward system
14. Create in-game Codex for algorithm explanations
15. Add leaderboard for challenge completion times

## LeetCode Integration Feature

This game uniquely incorporates coding challenges inspired by LeetCode problems, presenting them in two innovative ways:

### 1. Direct Prompts

- "Coding Shrines" or "Algorithm Altars" appear in dungeon rooms.
- Players interact with these to receive coding challenges.
- Solving challenges rewards the player with special items, stat boosts, or progression keys.

### 2. Visual Representations

- Coding problems are represented as visual puzzles or mini-games.
- Players solve these through game interactions rather than writing code.
- Examples include:
  - Two Sum: Balancing weighted crates on a scale.
  - Linked List Reversal: Rearranging mine carts on tracks.
  - Binary Tree Traversal: Platforming across tree-structured levels.
  - Depth-First Search: Navigating a maze to collect all items.

### Integration with Game Mechanics

- Difficulty scales with player progress.
- Rewards system ties challenge completion to in-game benefits.
- In-game "Codex" provides algorithm explanations.
- Optional hint system for struggling players.
- Speedrunning and leaderboard features for competitive players.

## Contributing

This project is primarily for personal learning, but suggestions and advice are welcome. Feel free to open an issue or submit a pull request if you have ideas for improvements or new features, especially related to the LeetCode integration or new visual puzzle concepts.

## License

This project is open source and available under the [MIT License](LICENSE).
