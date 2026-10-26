# 🎮 Neon 2048
### Beyond Numbers — A Neon-Powered Puzzle Adventure

An interactive 2048 puzzle game built with Python and Pygame, featuring a neon visual theme, evolving robot characters, smooth tile animations, multiple game modes, and score tracking.

## 🌐 Play Online

**Live Website:** *Coming soon — link will be added after deployment.*

The online version will be published after the Python desktop game is completed and tested.

## 🚀 Project Overview

Neon 2048 is a redesigned version of the classic 2048 puzzle game, developed for a Computational Thinking final project.

The game challenges players to slide numbered tiles across a grid, merge matching values, and reach higher numbers. It combines puzzle-solving with visual feedback, animations, and additional gameplay features to make the experience more engaging.

The project also demonstrates computational thinking concepts such as decomposition, pattern recognition, abstraction, algorithm design, and state management.

## 🎯 Project Objectives

- Implement the core 2048 game mechanics using Python.
- Create an engaging and visually distinctive interface.
- Apply algorithms to manage tile movement, merging, scoring, and game states.
- Explore problem-solving through different game modes and challenges.
- Develop a project that can be demonstrated locally and adapted for online play.

## ✨ Key Features

- **Neon Interface:** A dark background with colourful tiles and glowing visual effects.
- **Animated Tile Movement:** Smooth transitions when tiles move and merge.
- **Evolving Robot Characters:** Robot designs that change as tile values increase.
- **Score Tracking:** Current score, best score, and useful game statistics.
- **Undo and Restart:** Retry moves or start a new game.
- **Multiple Game Modes:** Classic, Zen, Time Attack, Puzzle, and local 1v1, subject to the implemented version.
- **Achievements and Challenges:** Additional goals to encourage replayability.
- **Hints:** Assistance with choosing a possible move.
- **Themes and Sound:** Customisation options for colours and optional sound effects.
- **Leaderboard and Records:** Track scores and player progress where supported.

*Features listed above describe the project goals. The final implementation may vary; see the actual game for available features.*

## 🧠 How the Game Works

1. The game starts with a grid containing numbered tiles.
2. The player moves tiles using the supported controls.
3. Tiles with matching values merge into a tile with their combined value.
4. A new tile appears after a valid move.
5. The score increases when tiles merge.
6. The game continues until the target tile is reached or no valid moves remain.

The implementation must ensure that each tile merges at most once per move and that invalid moves do not create extra tiles.

## 🧩 Computational Thinking Concepts

### 1. Decomposition
The project can be divided into separate components, such as the game board, tile movement, scoring, rendering, animation, and game modes.

### 2. Pattern Recognition
The game identifies matching tile values and possible moves on the grid.

### 3. Abstraction
The board can be represented as a two-dimensional data structure, while rendering and animations are handled separately.

### 4. Algorithm Design
Movement, merging, random tile generation, scoring, and game-over detection follow defined rules.

### 5. State Management
The game maintains information such as the board, score, current mode, undo history, and saved records.

## 🔄 Game Logic Workflow

Player Input → Validate Move → Slide Tiles → Merge Matching Tiles → Update Score → Spawn New Tile → Check Win/Game Over → Render Updated Board

## 🧰 Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core game logic and application code |
| Pygame | Game window, graphics, input handling, and animations |
| Python data structures | Board representation, scoring, and game state |
| JSON or another suitable storage method, if implemented | Saved scores, settings, and progress |

## 💻 Run Locally

### Prerequisites

- Python installed on your computer
- Git installed if you want to clone the repository

### 1. Clone the repository

Replace `YOUR_GITHUB_USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Neon-2048.git
cd Neon-2048
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

If the project contains a `requirements.txt` file:

```bash
python -m pip install -r requirements.txt
```

### 5. Launch the game

Use the actual entry-point filename in your project. For example, if the main file is `main.py`:

```bash
python main.py
```

The game should open in a separate window.

*Note: The commands above assume the repository contains the corresponding files. Adjust the entry-point filename if your project uses a different structure.*

## 🌍 Online Version and Deployment

The initial version is a Python desktop application built with Pygame.

Pygame is designed primarily for desktop applications, so publishing the game as a browser-based website requires an additional adaptation step.

The online version will aim to preserve the original game's visual style, game rules, and core features. The implementation and hosting platform will be documented once the browser version has been tested and deployed.

**Live Website:** To be added after deployment.

## 🧪 Testing

Important tests include:

- Tile movement in every supported direction.
- Correct merging and score updates.
- No double merging of the same tile in one move.
- No new tile after an invalid move.
- Correct win and game-over detection.
- Undo and restart behaviour.
- Game-mode rules and timer behaviour.
- Saving and restoring scores or settings, where implemented.

## 📌 Project Scope and Limitations

- The initial implementation is a desktop game using Python and Pygame.
- Online play requires a browser-compatible implementation or an appropriate adaptation.
- A local leaderboard does not automatically provide a shared online ranking system.
- Daily challenges and online rankings may require additional data storage or backend services if they are to be shared between users.
- The available features depend on the final tested implementation.

## 🎓 Academic Information

**Project:** Neon 2048 — An Enhanced Puzzle Game  
**Subject:** Computational Thinking  
**Project Type:** Interactive Python game and algorithmic problem-solving demonstration  
**Language:** Python  
**Game Library:** Pygame

## 🔮 Future Improvements

- Browser-based version with a shareable public URL.
- Online leaderboards and multiplayer support.
- More puzzle levels and custom challenges.
- Additional themes, animations, and sound options.
- Improved accessibility and gameplay statistics.

---

*Neon 2048 — Think strategically. Merge intelligently. Reach beyond 2048.*
