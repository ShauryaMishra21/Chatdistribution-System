⦁ Overview

This is a simple yet engaging implementation of the classic Snake game where the player controls a snake to eat food and grow longer while avoiding collisions with walls and itself.

⦁ Features

- Classic snake gameplay mechanics
- Real-time score tracking (snake length)
- Collision detection (walls and self)
- Game over and restart functionality
- Smooth keyboard controls

⦁ Requirements

- Python 3.x
- Pygame library

⦁ Installation

1. Install Python (if not already installed)
   - Download from [python.org](https://www.python.org/downloads/)
   - Ensure Python is added to PATH

2. Install Pygame
   bash
   pip install pygame
   

⦁ How to Run

1. Save the code as snake_game.py
2. Open terminal/command prompt in the file directory
3. Run the command:
   bash
   python snake_game.py
   

⦁ Controls

- Arrow Keys: Control snake direction
  - ↑ UP: Move up
  - ↓ DOWN: Move down
  - ← LEFT: Move left
  - → RIGHT: Move right

- Game Over Screen:
  - C: Play again
  - Q: Quit game

⦁ Game Rules

1. Guide the snake to eat red food blocks
2. Each food eaten increases snake length by 1
3. Avoid hitting the walls (screen boundaries)
4. Avoid running into the snake's own body
5. Game ends when collision occurs

⦁ Technical Details

# Configuration

python
WIDTH = 600          # Screen width
HEIGHT = 400         # Screen height
snake_size = 10      # Size of each snake segment
snake_speed = 15     # Game speed (FPS)


# Color Scheme

- Background: Black
- Snake: Green
- Food: Red
- Text: White/Red

# Game Mechanics

- Snake Movement: Grid-based (10px increments)
- Food Spawn: Random position on grid
- Collision Detection: Boundary and self-collision
- Growth Mechanism: Snake list appends on food consumption

⦁ Customization

You can easily modify the game by changing:

- Speed: Adjust snake_speed variable (higher = faster)
- Screen Size: Modify WIDTH and HEIGHT
- Colors: Change RGB values in color definitions
- Snake Size: Alter snake_size variable

⦁ Known Limitations

- Snake can reverse direction instantly (may cause self-collision)
- No score display during gameplay
- No difficulty progression
- No pause functionality

⦁ Future Enhancements

- Add score counter display
- Implement pause feature
- Add sound effects
- Create difficulty levels
- Add high score tracking
- Implement obstacles
- Add visual effects

⦁ Troubleshooting

#Issue: Pygame not found
- Solution: Ensure pygame is installed: pip install pygame

#Issue: Game window not responding
- Solution: Check Python version compatibility, reinstall pygame

#Issue: Game too fast/slow
- Solution: Adjust snake_speed variable

⦁ License

Free to use and modify for educational purposes.

⦁ Author
SHAURYA MISHRA
