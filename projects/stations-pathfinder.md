<h1 align="center">🚉 Stations Pathfinder</h1>

**[View Live Project](https://kood-sisu-stations-pathfinder.netlify.app/)**

Stations Pathfinder is a high-performance, command-line tool built in **Go** that optimizes train routing across complex network maps. It finds the most efficient paths for multiple trains to travel from a start to an end station, ensuring no collisions and minimal total travel time.

## ✨ Key Features
- **Optimal Pathfinding**: Uses Breadth-First Search (BFS) to find the shortest routes.
- **Collision Avoidance**: Implements disjoint path algorithms to prevent trains from sharing tracks or stations simultaneously.
- **Smart Scheduling**: Automatically balances multiple trains across available unique paths to minimize total turns.
- **Data Validation**: Rigorous checking of network map integrity (coordinates, connectivity, syntax).
- **Detailed Visualization**: Outputs colorful, step-by-step train movement logs in the terminal.

## 🛠️ Core Tech Stack
- **Language**: Go (Golang) 1.20+
- **Architecture**: Modular design (Pathfinding, Dispatching, Event Logging)
- **Dependencies**: Zero external dependencies (Standard Library only)

## 🌐 Web Visualization
An interactive Real-Time Dashboard was built to visualize the algorithms in action.

- **Front End**: Vanilla JavaScript, HTML5 Canvas, CSS3.
- **Back End**: Python http.server for local hosting.
- **Features**: Drag-and-drop map editing, live simulation playback, and responsive train tracking.

## 📺 Preview

[![Stations Pathfinder](../pic/stations.png)](https://kood-sisu-stations-pathfinder.netlify.app/)

[← Back to Profile](../README.md)
