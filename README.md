# Cognifind — Indoor Navigation System

Cognifind is an **indoor navigation system** that converts building floor plans into a **graph-based navigation model** and computes the **shortest path** between locations using classical pathfinding algorithms.

This project focuses on **accurate indoor routing**, where GPS fails, such as in educational institutions, offices, hospitals, and malls.

---

##  Project Overview

The system works by:

1. Taking a **floor map** as input
2. Identifying **walkable decision points (nodes)**
3. Connecting them using **walkable paths (edges)**
4. Assigning **distance weights**
5. Applying **A* algorithm** to find optimal routes

---

## Core Concept

* **Map** → Visual reference (floor plan)
* **Nodes** → Decision points (junctions, doors, stairs)
* **Edges** → Walkable connections
* **Weights** → Distances between nodes
* **Algorithm** → A* shortest path

> Navigation is treated as a **weighted graph problem**, not a drawing problem.

---

##  Tech Stack

* **Design Tool**: Inkscape (SVG-based map processing)
* **Data Format**: JSON
* **Algorithm**: A* (A-star)
* **Language**: Python / JavaScript (extendable)
* **Version Control**: Git & GitHub

---

##  Project Structure

```

```

---

##  Graph Representation

### Node Format

```json

```

### Edge Format

```json

```

---

##  Workflow



---

## 🎯 Features

* Accurate indoor navigation
* Graph-based routing
* Scalable to multi-floor buildings
* Clean separation of map and logic
* Algorithm-friendly data structure

---

## 🔮 Future Enhancements

* Multi-floor routing
* Outdoor + indoor hybrid navigation
* Real-world distance scaling
* Mobile application integration

---

## 👥 Team

* **Inayat Ul lah Wani**
* **Farhan Showket**
* **Nadia Khan**

---

## 📜 License

This project is for **academic and research purposes**.

---
