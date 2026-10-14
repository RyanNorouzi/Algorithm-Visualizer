# Algorithm Visualizer

An interactive PyQt6 application visualizing sorting, graph search, and pathfinding algorithms as generators.

## Features

- Visualize sorting algorithms: Bubble Sort, Merge Sort, Quick Sort, Heap Sort
- Visualize graph algorithms: Breadth-First Search (BFS), Depth-First Search (DFS), Dijkstra's algorithm
- Visualize pathfinding algorithms: A* and BFS on a 2D grid with interactive wall drawing
- Adjustable animation speed and array size
- Step-by-step algorithm execution via generator-based implementations
- Dark theme with color-coded steps for clarity
- Built with PyQt6 for a responsive desktop interface

## Getting started

Prerequisites: Python 3 (PyQt6 is installed from requirements.txt).

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`

## Project structure

- `main.py`: Application entry point
- `gui.py`: Main window with tabs and controls
- `visualizer.py`: Canvas widgets for sorting, graph, and grid visualization
- `sorting_algorithms.py`: Generator implementations of sorting algorithms
- `graph_algorithms.py`: Generator implementations of graph algorithms (BFS, DFS, Dijkstra)
- `pathfinding.py`: Generator implementations of A* and grid BFS
- `utils.py`: Shared constants, color palette, and helper functions
- `requirements.txt`: PyQt6 dependency

## License

Released under the MIT License (see LICENSE).
