# AI Shatranj Bot

<p align="center">
    <img alt="Screenshot" src="https://github.com/guru-divine/Shatranj-Bot/blob/main/Gameplay/bot_vs_bot.gif" width="1000">
</p>

An advanced terminal-based AI chess bot utilizing the Minimax algorithm with Alpha-Beta Pruning and an Evaluation Function for optimized decision-making. The bot supports various chess rules and offers multiple difficulty levels for a realistic gameplay experience.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Playing the Game](#playing-the-game)
  - [Command Line Options](#command-line-options)
- [Game Rules Implemented](#game-rules-implemented)
  - [Castling](#castling)
  - [En Passant](#en-passant)
  - [Fifty-Move Rule](#fifty-move-rule)
  - [Threefold Repetition](#threefold-repetition)
  - [Pawn Promotion](#pawn-promotion)
- [Levels of Difficulty](#levels-of-difficulty)
- [Contributing](#contributing)
- [License](#license)

## Features
- AI Chess Bot with Minimax algorithm and Alpha-Beta Pruning
- Supports Human vs Human and Human vs Bot gameplay
- Three levels of difficulty for AI bot
- Realistic chess rules including Castling, En Passant, Fifty-Move Rule, Threefold Repetition, and Pawn Promotion

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/guru-divine/Shatranj-bot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Shatranj-bot
    ```
3. Compile the game using the provided command:
    ```bash
    g++ Header/*.cpp main.cpp -std=c++11 -o chessbot
    ```

## Usage

### Playing the Game
Run the compiled game with:
```bash
./chessbot
```

### Command Line Options
You can start a game in different modes:
- **Human vs Human**: Both players are human
- **Human vs Bot**: Play against the AI bot
To choose a specific mode, follow the prompts after starting the game.

## Game Rules Implemented

### Castling
Castling is a move involving the king and either of the original rooks.

### En Passant
Special pawn capture that can occur immediately after a pawn moves two ranks forward from its starting position.

### Fifty-Move Rule
If fifty moves are made by each side without a pawn move or capture, the game can be drawn.

### Threefold Repetition
A player can claim a draw if the same position occurs three times with the same player to move and all possible moves being the same.

### Pawn Promotion
Pawns reaching the far side of the board can be promoted to a queen, rook, bishop, or knight.

## Levels of Difficulty
- **Easy**: Basic AI with shallow search depth.
- **Medium**: Intermediate AI with moderate search depth.
- **Hard**: Advanced AI with deeper search and evaluation.


## Contributing

We welcome contributions from the community! Here’s how you can contribute:

1. **Fork the Repository**: Click on the "Fork" button at the top right of this page to create a copy of the repository in your GitHub account.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
    ```bash
    git clone https://github.com/guru-divine/Shatranj-bot.git
    ```
3. **Create a Branch**: Create a new branch for your changes.
    ```bash
    git checkout -b feature-branch-name
    ```
4. **Make Changes**: Make your changes to the code or documentation.
5. **Commit Changes**: Commit your changes with a descriptive message.
    ```bash
    git commit -am 'Add a descriptive commit message'
    ```
6. **Push Changes**: Push your changes to your fork.
    ```bash
    git push origin feature-branch-name
    ```
7. **Create a Pull Request**: Go to the original repository and open a pull request with a clear description of your changes and why they are beneficial.

### Code of Conduct

Please note that this project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

Feel free to open an issue if you have any questions or need further guidance.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as long as the following conditions are met:

- Attribution: You must give appropriate credit to the original author.
- No Warranty: The software is provided "as is", without warranty of any kind.

For more details, please see the [LICENSE](LICENSE) file.

