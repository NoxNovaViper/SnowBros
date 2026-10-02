# SnowBros

SnowBros is a C++ action-platformer inspired by classic snowball-based arcade gameplay. The project contains a full game implementation using SFML for rendering, input, audio, and gameplay systems.

The repository includes a large set of gameplay classes, level data, UI screens, enemy logic, projectiles, player systems, and asset folders.

## Overview

This project is structured as a game development codebase for a side-scrolling action game with:

- Player movement and combat
- Enemy AI and boss behavior
- Snowball/projectile mechanics
- Level progression and game states
- Menus, HUD, and leaderboard systems
- Character selection and login flow
- Asset loading from external sprite and sound folders

## Tech Stack

- C++
- SFML
- Visual Studio project files
- Text-based level data files
- External asset directories

## Project Structure

```text
.
├── ProjectOop/
│   ├── main.cpp
│   ├── mainmenu.cpp / .h
│   ├── loginScreen.cpp / .h
│   ├── characterChoiceUI.cpp / .h
│   ├── Player.cpp / .h
│   ├── Enemy.h
│   ├── EnemyFactory.cpp / .h
│   ├── Boss.h / .cpp
│   ├── Snowball.cpp / .h
│   ├── Tornado.cpp / .h
│   ├── Knife.cpp / .h
│   ├── Physics.cpp / .h
│   ├── LevelManager.cpp / .h
│   ├── HUD.cpp / .h
│   ├── shop.cpp / .h
│   ├── PauseMenu.cpp / .h
│   ├── GameOverUI.cpp / .h
│   ├── LeaderboardUI.cpp / .h
│   ├── level1.txt ... level10.txt
│   ├── levels.txt
│   ├── users.txt
│   ├── ProjectOop.slnx
│   ├── ProjectOop.vcxproj
│   ├── ProjectOop.vcxproj.filters
│   └── ProjectOop.vcxproj.user
├── SnowBrosAssets/
│   ├── Level1 ... Level10
│   ├── player_red / player_green
│   ├── EnemySprites
│   ├── BossSprites
│   ├── Snowball
│   ├── Sounds
│   ├── Fonts
│   ├── Images
│   └── other sprite folders
├── uml_entities_projectiles_collectibles.png
├── uml_ui_game_management.png
├── SnowBros_Report.docx
├── SnowBros_Report_Final.docx
└── README.md
```

## Gameplay Features

- Side-scrolling action gameplay
- Snowball-based combat system
- Multiple enemy types and bosses
- Character selection and progression
- Level-based challenges
- HUD, score tracking, and game-over flow
- Menu-driven workflow with leaderboard support

## Game Architecture Notes

The game is organized into multiple systems rather than a single monolithic file, including:

- Player logic
- Enemy and boss AI
- Projectile behavior
- Physics
- Asset loading
- UI management
- Level management
- Data persistence for users and progress

## Running the Project

This repository is a Visual Studio C++ project and is designed for Windows-based development. To run it locally:

1. Open `ProjectOop/ProjectOop.slnx` in Visual Studio or the appropriate C++ IDE.
2. Restore or configure the required SFML dependencies.
3. Build the solution.
4. Run the executable.

## Dependencies

The project currently relies on SFML and Windows-style Visual Studio tooling for development and runtime support.

## Notes

This is a game project with many gameplay and UI systems already implemented, and the repository includes both source code and several asset folders and UML diagrams for design documentation.

## License

No explicit license file is present in the repository root. If you intend to publish or distribute this project publicly, consider adding a license that matches your intended use.
