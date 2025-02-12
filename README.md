# Wall and Mines

This project implements a simple game in C#. Players navigate through a grid filled with walls and mines, collecting items and avoiding enemies. The game keeps track of player scores, energy, and mines collected.

## Project Overview

The project consists of a single C# class:
- `Program.cs`: The main class that runs the game and contains all the game logic.

### Features

The game includes:
1. Generating a grid with random walls and items.
2. Placing and navigating a player character.
3. Spawning and moving enemies.
4. Collecting items to increase score and energy.
5. Placing mines to destroy enemies.
6. Displaying game stats such as time, energy, score, and mines.

## Requirements

The project requires .NET SDK to compile and run the C# files.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/barissolcay/Wall-and-Mines.git
    cd Wall-and-Mines
    ```

2. Build the project:

    ```bash
    dotnet build
    ```

3. Run the game:

    ```bash
    dotnet run --project Wall-and-Mines
    ```

## Game Flow

1. The game initializes a grid with random walls and items.
2. The player character is placed at a random position on the grid.
3. The player navigates through the grid using arrow keys, collecting items and avoiding enemies.
4. The player can place mines using the spacebar to destroy enemies.
5. The game ends when the player's energy reaches zero or the player collides with an enemy.

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
