# Chess Game Project

## Table of Contents
- [Getting Started](#getting-started)
  - [Summary Of What's Needed](#summary-of-whats-needed)
  - [How To Run The Project Locally](#how-to-run-the-project-locally)
- [Project Overview](#project-overview)

## Getting Started

### Summary Of What's Needed
- Clone repo
- Install Pygame (`pip install pygame`)
- Local images folder with chess piece images

Please refer to the detailed instructions below.

### How To Run The Project Locally
After setup, run the following command:
```
python main.py
```


### Step By Step Setup Instructions
(0.0) Clone the Repository:
Open your terminal, navigate to the desired location (e.g., Desktop), and run the following command:

```
git clone <repository-url>
```
Replace <repository-url> with the actual repository URL.

(0.1) Navigate to Project Directory
Navigate to the project directory using the terminal:
```
cd chess-game-project
```

(1) Install Pygame
Install the Pygame library using the following command:
```
pip install pygame
```

(2) Run the Game
Start the game by running the following command:
```
python main.py
```

(3) Play the Game
1. Open a web browser and visit http://localhost:400 to play the chess game.
2. Click on pieces to select them and click on valid squares to move.

(4) Quit the Game
Close the game window to exit the game.


## Project Overview
Core Logic: engine.py defines the chess game's core logic and rules.  
User Interface: main.py creates the Pygame interface for the game.  
Chess Pieces: pieces folder contains chess piece images.  
Styling: The game features basic board styling and piece images.  
Interaction: Players can select and move pieces using mouse clicks.  


## Conclusion
The chess game project is a simple implementation of a two-player chess game using Pygame. By following the setup instructions, you can run the game locally, play chess, and enjoy a basic chess experience. The project provides a foundation for further development and customization, such as adding new features, enhancing the UI, and refining the gameplay mechanics.
