# NetLogo-DropletSimulation

## 🌧️ Overview

**NetLogo-DropletSimulation** is an agent-based model simulating the flow and distribution of humidity in a 2D grid of patches. The simulation explores how localized increases in humidity lead to the formation and downward movement of "droplets" that travel based on surrounding patch humidity. It uses NetLogo's patch and neighbor mechanics to visualize how moisture spreads and collects over time.

---

## 🧪 Features

- Patch-based simulation of humidity accumulation
- Random activation of "awake" patches that contribute to humidity buildup
- Droplet generation once a humidity threshold is reached
- Intelligent droplet movement toward patches with higher humidity below
- Dynamic color scaling based on local humidity levels

---

## 🧩 Concepts

This model demonstrates basic principles of:
- Diffusion-like behavior across cellular grids
- Moisture accumulation and dissipation
- Rule-based agent interaction using NetLogo's patch primitives

---

## 📷 Screenshot
<img width="975" height="816" alt="Screenshot 2025-07-30 130120" src="https://github.com/user-attachments/assets/42a8d31f-41fb-472c-9fbb-6df898bda782" />

---

## 🚀 Getting Started

### Requirements

- [NetLogo](https://ccl.northwestern.edu/netlogo/) (version 6.0 or later recommended)

### Running the Simulation

1. Clone the repository:
git clone https://github.com/yourusername/NetLogo-DropletSimulation.git

2. Open droplet-simulation.nlogo in NetLogo.

3. Click the Setup button to initialize the grid.

4. Click Go to run the simulation.

5. (Optional) Adjust the awake_cells slider to control how many patches activate each tick.

---

## 🔧 Parameters
Parameter	Description
awake_cells	Determines the number of active patches per timestep
Humidity Threshold	A droplet is triggered when humidity ≥ 50

---

## 📁 File Structure
bash
Copy
Edit
NetLogo-DropletSimulation/
├── droplet-simulation.nlogo     # NetLogo model file
├── README.md
└── images/
    └── simulation_screenshot.png

---
    
## 📚 License
This project is licensed under the MIT License. See LICENSE for details.
