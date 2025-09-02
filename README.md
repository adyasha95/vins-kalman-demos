# Visual-Inertial Navigation System (VINS) Basics – Kalman Filter Demos

This repository contains a Jupyter Notebook (`vns.ipynb`) with beginner-friendly simulations of **Kalman Filters**, designed to build intuition for **Visual-Inertial Navigation Systems (VINS)**.

---

## 🚀 Contents
- **1D Kalman Filter**  
  Simulates a car moving at constant velocity with noisy GPS-like measurements.  
  Shows how the Kalman Filter fuses predictions and measurements to reduce noise.

- **2D State Model (Position + Velocity)**  
  Extends to a matrix form where the state includes both position and velocity.  
  Demonstrates how uncertainty propagates and how updates refine the estimate.

- **Plots & Visualizations**  
  Each simulation produces plots comparing:
  - True position/trajectory
  - Noisy sensor measurements
  - Kalman Filter estimates

---

## 📂 Repository Structure
```
vns-kalman-demos/
│── vns.ipynb           # Jupyter Notebook with simulations
│── README.md           # Project documentation
│── requirements.txt    # Python dependencies
│── .gitignore          # Ignore cache/virtual env files
````

---

## 🔧 Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/adyasha95/vns-kalman-demos.git
cd vns-kalman-demos
pip install -r requirements.txt
