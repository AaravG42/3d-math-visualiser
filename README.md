# 3D Math Visualizer

## Overview
The **3D Math Visualizer** is a standalone JavaScript tool designed to render and interact with 3D mathematical objects using **A-Frame**. It supports visualizing vectors, explicit surfaces, parametric surfaces, and implicit surfaces in real-time, making it ideal for educational and exploratory purposes.

---

## Key Features

### **Vector Visualization**
- Add 3D vectors with customizable components and colors.
- Proper alignment using quaternion-based rotation.

### **Explicit Surfaces**
- Render surfaces defined by `z = f(x, y)` with adjustable range, resolution, and color.

### **Parametric Surfaces**
- Define surfaces using parametric equations `x(u, v)`, `y(u, v)`, `z(u, v)` with customizable parameter ranges.

### **Implicit Surfaces**
- Render surfaces defined by `f(x, y, z) = 0` using:
  - Parametric conversion, or
  - The Marching Cubes algorithm (for unsupported functions).

### **Grid and Axes**
- 3D gridlines in **XY**, **YZ**, and **ZX** planes for spatial reference.
- Always-visible **X**, **Y**, **Z** axes with labeled markers.

### **Camera Controls**
- Orbit, zoom, and pan controls with reset functionality.

### **Math Expression Evaluation**
- Uses **Math.js** for evaluating mathematical expressions.
- Supports advanced functions and constants.

### **Object Management**
- Add, remove, and clear objects programmatically.

---

## Motivation
The project aims to make abstract mathematical concepts tangible by providing an interactive 3D environment. It is designed for **educators**, **students**, and **enthusiasts** to explore and visualize mathematical operations and surfaces intuitively.

---

## Summary
The **3D Math Visualizer** combines **A-Frame** for rendering and **Math.js** for computation, offering a robust platform for 3D mathematical visualization. It is a versatile tool for **education**, **experimentation**, and **exploration** of mathematical concepts.
