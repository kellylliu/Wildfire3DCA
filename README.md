# Modeling 3D Fire Spread Using Cellular Automata

## Overview

This project implements a **three-dimensional stochastic Cellular Automaton (CA)** to model wildfire spread and optimize suppressant deployment. Highlights include:

- A fully 3D CA model extending classic 2D forest-fire frameworks  
- Realistic wildfire dynamics: ignition probability, neighbor interaction, environmental layering  
- Visualization of fire propagation through 3D grids  
- Algorithm to identify optimal suppressant placement for containment

---

## Methods & Features

### 1. Cellular Automaton Mechanics  
- Discrete 3D lattice of cubic cells  
- States: **Unburned**, **Burning**, **Burned**  
- Transition rules account for neighboring burning cells and probabilistic ignition rates

### 2. 3D Wildfire Propagation  
- Visualizes volumetric flame spread, revealing fire plume effects absent in 2D  
- Layer-by-layer evolution illustrating depth and spatial complexity

### 3. Suppressant Optimization  
- Models suppressant deployment through user-defined “blocks”  
- Simulates suppression outcomes; tunes placement to minimize spread while conserving resources

### 4. Interactive UI Controls  
- Adjustable parameters: ignition probability, neighborhood radius, suppressant capacity  
- Dynamic plots that update CA evolution and suppression efficacy in real-time

---

## Installation & Usage

### Prerequisites  
- [Wolfram Mathematica or Wolfram Engine](https://www.wolfram.com) (v12 or newer)

### Setup  
1. Clone or download this repo  

### Running the Model  
- Adjust CA parameters via input fields  
- Run sections in sequence: CA setup ➜ Fire evolution ➜ Suppression  
- View results via 3D plots and performance metrics

### Customization  
- Tweak grid size, fire rules, and suppressant layout  
- Try multiple runs to test strategy robustness

---

## Visuals

- 3D arrays showing fire progression across voxels at each time step  
- Supplementary 2D cross-sections for clarity  
- Optimized suppressant placement overlayed on burning area graphs

