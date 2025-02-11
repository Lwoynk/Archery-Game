# Battle Arena Game

A C# console-based battle arena game where players compete in a coordinate system with unique health and set values.

## 🎮 Game Description

This game simulates a battle arena where three characters (A, B, and C) fight based on their positions, health values, and set numbers in a 20x20 coordinate grid (-10 to 10 on both axes).

## 🎯 Features

- Interactive coordinate-based gameplay
- Visual grid system with colored characters
- Random character placement
- Health and set system
- Distance-based combat
- Score calculation
- Multiple round battles
- Visual battle state representation

## 🎲 Game Rules

### Character Properties
- Each character has:
  - Position (x,y coordinates)
  - Health (60, 80, or 100)
  - Set number (1, 2, or 3)

### Battle Mechanics
1. Player places character A
2. Characters B and C are randomly placed
3. Battles occur between closest characters
4. Combat is determined by:
   - Set number differences
   - Manhattan distance
   - Character health
5. Characters turn red when defeated

### Scoring System
- Score calculation: `(Manhattan distance × 10) + (100 - (health - 25))`
- Higher scores win
- Health reduces by 25 after combat

### Distance Rules
- Characters must be within 15 units to battle
- Manhattan distance affects scoring
- Battles occur between closest pairs first

## 🚀 Getting Started

### Prerequisites
- .NET Framework or .NET Core
- Visual Studio or any C# compatible IDE
- Windows OS (for console features)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/barissolcay/Archery-Game.git
