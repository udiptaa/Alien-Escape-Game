# Alien Escape Game

A 3D maze game where you play as an alien trying to escape from guards using different pathfinding algorithms.

## 🎮 Game Features

- 6 challenging levels with increasing difficulty
- Multiple pathfinding algorithms for guard AI:
  - Breadth-First Search (BFS)
  - A* Search
  - Greedy Best-First Search
- 3D graphics using Three.js
- Dynamic lighting and shadows
- Key collection and door unlocking mechanics
- Time-based challenges
- Mouse and keyboard controls
- Level selection feature

## 🚀 How to Play

1. Open `advanced_game.html` in a modern web browser
2. Use WASD or Arrow keys to move
3. Collect all keys to unlock the door
4. Avoid guards and reach the exit before time runs out
5. Complete all 6 levels to win
6. Press 1-6 to jump to any level

## 🎯 Game Rules

- Each level has a time limit
- Collect all keys to unlock the exit door
- Avoid guards - they will catch you if they touch you
- Guards use different pathfinding algorithms to track you
- Complete the level within the time limit
- Level 6 has special guards using different algorithms

## 🛠️ Technical Details

- Built with Three.js for 3D graphics
- Uses GLTFLoader for 3D models
- Implements multiple pathfinding algorithms
- Responsive design that works on different screen sizes
- Optimized guard speeds for balanced gameplay

## 📋 Requirements

- Modern web browser with WebGL support
- No additional installation required
- Internet connection for loading Three.js and models

## 🎨 Level Design

1. **Training Ground**
   - Basic level with 1 guard and 1 key
   - Introduction to game mechanics
   - Guard Speed: 0.08

2. **Security Checkpoint**
   - 2 guards, 2 keys and 2 doors
   - More complex maze layout
   - Guard Speed: 0.09

3. **Research Lab**
   - 2 guards, 3 keys and 3 doors
   - Challenging guard patterns
   - Guard Speed: 0.11

4. **Control Room**
   - 2 guards, 4 keys and 4 doors
   - Strategic gameplay required
   - Guard Speed: 0.12

5. **Escape Route**
   - 2 guards, 5 keys and 5 doors
   - Guards switch between different algorithms
   - Guard Speed: 0.13

6. **Final Challenge**
   - 3 guards using different algorithms simultaneously
   - 6 keys and 6 doors
   - Ultimate test of skill and strategy
   - Guard Speed: 0.15

## 🎯 Controls

- **W/↑**: Move forward
- **S/↓**: Move backward
- **A/←**: Move left
- **D/→**: Move right
- **Arrow Keys**: Alternative movement controls
- **Mouse**: Click and drag to move
- **Space**: Continue to next level
- **Restart Button**: Restart the game
- **Level Selection**: Press 1-6 to jump to specific level

## 🔧 Development

This game was developed as a demonstration of different pathfinding algorithms in a 3D environment. The code is structured to be easily modifiable and extensible.

## 📝 License

This project is open source and available under the MIT License.

## 👥 Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## 📧 Contact

For any questions or suggestions, please open an issue in this repository.

## 📁 Project Structure

```
📁 Alien-Escape-Game/
├── 📄 advanced_game.html    (Main game file)
├── 📄 README.md            (Project documentation)
├── 📄 LICENSE             (MIT License)
└── 📄 .gitignore          (Git ignore file)
```
