# Planet Simulation

A simple 2D solar system simulation built with Python and Pygame. This project simulates the gravitational forces and orbits of the Sun, Earth, Mars, Mercury, and Venus using basic physics formulas.

## Features
- Real-time simulation of planetary orbits.
- Displays the distance of each planet from the Sun.
- Accurate relative masses and starting velocities for a realistic orbital simulation.

## Requirements
- Python 3.x
- Pygame

## Installation

1. Ensure you have Python installed on your system.
2. Install the required dependency:
   ```bash
   pip install pygame
   ```

## Usage

Run the `main.py` file to start the simulation:

```bash
python main.py
```

## How It Works
The simulation uses Newton's law of universal gravitation to calculate the forces between the celestial bodies and updates their positions over time using a defined timestep. The orbits are visualized by drawing lines tracking the positions of each planet.

## Controls
- Close the window to stop the simulation.
