# Archery Game

This project simulates an archery game where three players (A, B, and C) are positioned on a coordinate system. The game calculates distances between players and determines the winner based on set rules.

## Project Overview

The project consists of a single C# program that performs the following tasks:
1. Prompts the user to enter coordinates for player A.
2. Generates random coordinates for players B and C.
3. Calculates distances between players.
4. Ensures no two players are at the same coordinates.
5. Assigns random sets and health values to each player.
6. Displays the coordinates, sets, and health of each player.
7. Simulates rounds of battles between players based on their distances and sets.
8. Determines and displays the winner based on the scores.

### Features

The game includes:
1. User input validation for player A's coordinates.
2. Random generation of coordinates for players B and C.
3. Distance calculation between players.
4. Random assignment of sets and health values.
5. Display of a coordinate system with players' positions.
6. Simulation of battles based on sets and distances.
7. Display of the winner and their score.

## Requirements

The project requires .NET Core SDK to compile and run the C# files.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/barissolcay/Archery-Game.git
    cd Archery-Game
    ```

2. Compile the C# files:

    ```bash
    dotnet build
    ```

3. Run the program:

    ```bash
    dotnet run --project final_code.csproj
    ```

## Game Flow

1. The player is prompted to enter coordinates for player A (Ax and Ay) within the range [-10, 10].
2. The program generates random coordinates for players B and C.
3. The distances between players are calculated, and the program ensures no two players share the same coordinates.
4. Each player is assigned a random set and health value.
5. The program displays the coordinates, sets, and health of each player.
6. The program simulates rounds of battles between players based on their distances and sets.
7. The winner is determined based on the scores, and the result is displayed.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs.

## License

MIT License

```markdown
MIT License

Copyright (c) 2025 Baris Solcay

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
