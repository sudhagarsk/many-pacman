# PacMan Game Simulation

This project simulates multiple PacMan characters moving randomly across the screen. PacMen can be added dynamically, and their movement is controlled using two buttons: one to add PacMen and another to start the movement.

## Features

- **Add PacMen**: You can create new PacMen on the screen at random positions by clicking the "Add PacMan" button.
- **Move PacMen**: All PacMen move randomly around the screen after pressing the "Start Game" button.
- **Collision Detection**: PacMen change direction when they reach the boundaries of the screen.
- **Animated PacMen**: PacMan images alternate between open and closed mouths to simulate movement.

## Technologies Used

- **HTML5**: Provides the structure of the web page.
- **JavaScript**: Handles the logic for adding, moving, and animating the PacMen.

## How It Works

1. **Adding PacMan**: Each click on the "Add PacMan" button generates a new PacMan at a random position with a random velocity.
2. **Starting Movement**: The "Start Game" button begins moving all the PacMen on the screen. The PacMen bounce off the walls when they reach the edge of the screen.
3. **PacMan Animation**: The PacMan's appearance alternates between two images to simulate an opening and closing mouth.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pacman-simulation.git
