# A* Pathfinding Visualizer

This repository contains a Python implementation of an A* pathfinding visualizer. The project aims to simulate a robot's navigation through obstacles and determine the shortest path from a specified starting point to a target destination.

## Features

- Implemented the A* pathfinding algorithm in Python to find the optimal path.
- Utilized the Manhattan distance as an admissible heuristic to guide the search process.
- Enhanced the user experience with interactive obstacle placement, point selection, and real-time visualization.
- Leveraged the Pygame library for graphical rendering and interactivity.

## Getting Started

To get started with the A* Pathfinding Visualizer, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/A-Star_Pathfinding_Visualizer.git`
2. Navigate to the project directory: `cd A-Star_Pathfinding_Visualizer`
3. Install the required dependencies: `pip install pygame`
4. Run the visualizer: `python visualizer.py`

## Usage

Upon running the visualizer, you will be presented with a graphical interface where you can interact with the following components:

- **Start and End Points**: Click on any two grid cells to set the starting and target destinations for the robot.
- **Obstacle Placement**: Click and drag the mouse to place obstacles on the grid, representing areas that the robot cannot traverse.
- **Visualization**: After placing the obstacles and setting the start and end points, click 'spacebar' to start the visualization, the A* algorithm will automatically find the shortest path and display it on the grid in real-time.



## Acknowledgments

- The A* algorithm implementation was inspired by [Xueqiao (Joe) Xu's article](https://towardsdatascience.com/a-star-a-search-algorithm-eb495fb156bb) on Towards Data Science.
- The visualization and user interaction components were made possible by the Pygame library.


Happy pathfinding!
