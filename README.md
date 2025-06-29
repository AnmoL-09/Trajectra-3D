# Trajectra 3D

A 3D pathfinding visualization tool inspired by Micromouse robotics competitions. This project demonstrates various maze generation and pathfinding algorithms in an interactive 3D environment using Three.js.

## 🎯 Project Overview

This project was developed as an experiment to visually demonstrate how pathfinding robots operate. Inspired by my experience with the Micromouse robotics competition, I needed a robust maze generator. To enhance both the challenge and the visual appeal, I chose to render everything in 3D using Three.js, which made the process smoother than expected.

## 🚀 Features

- **Interactive 3D Visualization**: Explore mazes and pathfinding algorithms in a beautiful 3D environment
- **Multiple Pathfinding Algorithms**: Compare different approaches to solving mazes
- **Various Maze Generation Methods**: Generate mazes using different algorithms
- **Real-time Visualization**: Watch algorithms work in real-time with step-by-step visualization
- **Educational Tool**: Perfect for learning about pathfinding and maze generation concepts

## 📚 Pathfinding Algorithms

### A* Algorithm
Widely regarded as one of the most effective and popular pathfinding methods, A* is known for its completeness, optimality, and efficiency. It uses weights and always finds the shortest route.

### Depth First Search
Originating from 19th-century research by Charles Pierre Trémaux, this strategy is often used for maze solving. It does not use weights and does not guarantee the shortest path.

### Dijkstra's Algorithm
Conceived by Edsger W. Dijkstra in 1956, this classic algorithm is a staple in pathfinding. It is weighted and ensures the shortest path is found.

### Greedy Best First Search
Unlike A*, this approach only considers the estimated distance to the goal, ignoring the start node. It is weighted but does not guarantee the shortest route.

## 🏗️ Maze Generation Algorithms

### Recursive Division
This algorithm treats the maze as a fractal, starting with an empty grid and progressively adding walls. The result is a visually striking maze, with each step introducing more intricate detail.

### Depth First Search
Known for its speed and simplicity, this method creates mazes with long corridors and few branches by exploring as far as possible before backtracking.

### Kruskal's Algorithm
Used to generate minimal spanning trees, Kruskal's method produces mazes with regular, easily solvable patterns due to the equal weighting of all walls.

### Prim's Algorithm
Unlike Kruskal's, Prim's algorithm begins at a single point and expands outward, gradually building the maze from the inside out.

## 🛠️ Technologies Used

- **Three.js**: 3D graphics library for web browsers
- **JavaScript**: Core programming language
- **HTML5/CSS3**: Structure and styling
- **GitHub Pages**: Deployment platform

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

- **Author**: Anmol Mahobiya
- **Project Link**: [https://github.com/AnmoL-09/Trajectra-3D](https://github.com/AnmoL-09/Trajectra-3D)

---

*Built with ❤️ for the robotics and algorithm visualization community*
