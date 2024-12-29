
# LudoStar

## Overview
LudoStar is a modern take on the timeless board game Ludo, built in Python with OpenGL graphics. Designed for 4 players, this project brings the excitement of Ludo to the digital space, with stunning graphics and seamless animations.

## Features
- **Realistic Gameplay:** Dice rolling mechanics and token movements true to the original game.
- **Player Interaction:** Handles turn-based actions with support for consecutive sixes and bonus moves.
- **Customizable Board:** Easily modify board dimensions and aesthetics.
- **Graphical Enhancements:** Smooth animations, blinking indicators, and an intuitive interface.

## Installation

### Requirements
- Python 3.6+
- OpenGL (`PyOpenGL`)
- GLFW (`pyGLFW`)
- GLUT (optional, depending on your system setup)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LudoStar.git
   cd LudoStar
   ```
2. Install dependencies:
   ```bash
   pip install PyOpenGL pyGLFW
   ```
3. Run the game:
   ```bash
   python ludoStar.py
   ```

## How to Play
1. Each player takes turns rolling the dice.
2. Move tokens based on dice outcomes.
3. Follow standard Ludo rules to get all your tokens to the goal.

### Game Rules
1. Each player starts with four tokens in their home area.
2. A player must roll a six to move a token from home onto the board.
3. Once on the board, tokens move clockwise based on dice outcomes.
4. Rolling a six grants an extra turn. Rolling three consecutive sixes skips the turn.
5. Tokens can "capture" opponent tokens by landing on the same space, sending the captured token back to its home area.
6. The objective is to move all four tokens to the finish area before the other players.

## Known Issues
- Some platforms may require specific OpenGL or GLFW configurations.
- Performance may vary on systems with limited graphical resources.

## Future Enhancements
- Add AI players for single-player gameplay.
- Include additional themes and sound effects.
- Implement networked multiplayer for remote play.

## Contribution
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License
This project is licensed under the MIT License. See `LICENSE` for more information.

## Contact
For queries or suggestions, contact [faiyazahmed.2k2@gmail.com].
