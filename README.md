

---

# Campus Navigation System

## 📌 Overview
The **Campus Navigation System** is an interactive application designed to help users find the shortest path between their current location and a specified destination within a campus. The system leverages **Dijkstra's algorithm** to calculate the most efficient route and provides users with a clear, step-by-step guide to reach their destination.

## ✨ Features
- 🚩 Locate the shortest path between two points within the campus.  
- ⚡ Efficient route calculation using Dijkstra's algorithm.  
- 💻 User-friendly interface for inputting start and destination points.  
- 🗺️ Visual representation of the campus map (if applicable).  


## 🚀 Usage

1. **Open the application.**  
2. **Enter your current location and desired destination.**  
3. **The system will calculate the shortest path using Dijkstra's algorithm.**  
4. **Follow the displayed path to reach your destination.**  

## 🧠 Algorithm

The system uses **Dijkstra's algorithm** to find the shortest path. The key steps are:

1. Initialize the distance of the starting point to zero and all other points to infinity.  
2. Use a priority queue to explore the nearest unvisited node.  
3. Update the distance of neighboring nodes if a shorter path is found.  
4. Repeat the process until the destination is reached or all nodes are visited.  
5. Backtrack to construct the shortest path from start to destination.  

## 🛑 Example

```
Start: Library  
Destination: Cafeteria  
Shortest Path: Library ➡️ Science Building ➡️ Cafeteria  
Distance: 450 meters  
```


## 📄 License

This project is licensed under the **MIT License**.

---
