# Chess-Bot
This project is a console-based Chess Bot implemented in C++. The bot can play chess against a human player or another bot, and supports bot-vs-bot games as well. It uses various game logic and search algorithms to determine the best possible moves.

Project Structure

Chess-Bot/
|-- main.cpp          # Entry point of the program
|-- bot.cpp           # Chess bot logic
|-- player.cpp        # Player-related functionality
|-- chess.cpp         # Core game logic
|-- path_node.cpp     # Pathfinding and decision-making algorithms
|-- chess.h           # Header file with class and function declarations
|-- README.md         # Project documentation

Features

Human vs Bot gameplay

Bot vs Bot simulation

Move validation and game state checks

Alpha-beta pruning algorithm for optimal bot decisions

Cross-platform support for Linux environments (like GitHub Codespaces)

Compile the project:

g++ main.cpp bot.cpp player.cpp chess.cpp path_node.cpp -o chess_bot

Run the chess bot:

./chess_bot

