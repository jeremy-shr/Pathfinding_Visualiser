# Pathfinding Algorithm Comparison Tool

This program is a Python-based tool that provides a graphical user interface for visualizing and comparing two pathfinding algorithms: A* and Dijkstra's. The tool utilizes the Pygame library for drawing and visualization.

## Getting Started

To use this tool, follow these steps:

1. Ensure you have Python and Pygame installed on your system.
   
2. Clone or download this repository to your local machine.

3. Open a terminal and navigate to the directory containing the program.

4. Run the program by executing the following command:
   ```
   python astar.py
   ```

5. The graphical user interface will open, allowing you to interact with the tool.

## Usage

- **Left Click**: You can interact with the grid using the left mouse button.
  - Click once to set the start point (orange node).
  - Click again to set the end point (turquoise node).
  - Click on any other cell to create barriers (black nodes) that the pathfinding algorithms will avoid.

- **Right Click**: You can clear a cell by right-clicking it. You can also clear the start and end nodes.

- **Spacebar**: When both a start and an end node are placed on the grid, you can press the Spacebar to execute the A* algorithm and find the shortest path.

- **'d' Key**: Press the 'd' key to execute Dijkstra's algorithm and find the shortest path.

- **'c' Key**: Press the 'c' key to clear the grid, removing all nodes and barriers.

## Supported Algorithms

This tool supports two pathfinding algorithms:

1. **A* Algorithm**: Finds the shortest path using the A* algorithm, indicated by the orange start node and turquoise end node.

2. **Dijkstra's Algorithm**: Finds the shortest path using Dijkstra's algorithm.

## Visualization

The grid is displayed on the Pygame window, with visual representations of nodes in various colors:

- White: Unvisited nodes.
- Black: Barrier nodes to be avoided.
- Orange: Start node.
- Turquoise: End node.
- Green: Nodes in the open set (visited but not finalized).
- Red: Nodes in the closed set (visited and finalized).
- Purple: Nodes that form the final path.

## Output

After running an algorithm, the program will display the time taken to find the shortest path. This information regarding time taken to reach point will be printed in the terminal.

## Customization

You can customize the program by adjusting the grid size and other parameters in the code. Feel free to modify the program to suit your needs or use it as a base for your pathfinding projects.

## Acknowledgments

This program was created using the Pygame library and is intended for educational purposes and algorithm comparison. It provides a visual representation of the A* and Dijkstra's pathfinding algorithms. This program was used in my IB Maths essay on the effect of an algorithm's running environment on its efficiency. 

---

**Note:** Ensure that you have the necessary dependencies, especially Pygame, installed before running the program.

Have fun exploring and comparing pathfinding algorithms!
