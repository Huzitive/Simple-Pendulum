# 🔮 Neon Pendulum Simulation

**A beautifully crafted pendulum physics simulator with glowing visuals, accurate motion, and live graphing.**


> 🌐 Created by **Huzaifa**  
> 🎓 Guided by **Miss Mariam Ghulam Nabi**  
> 🏫 NEDUET Physics Department

---

## ✨ Features

- ⚙️ **Realistic Physics**: Accurate gravitational acceleration and pendulum dynamics.
- 💡 **Neon Aesthetics**: Styled with glowing effects and dark gradients.
- 🎵 **Tick-Tock Sound**: Periodic audio feedback synced with peak motion.
- 📈 **Live Angle Graph**: Real-time plotting of angular displacement.
- ⚡ **Energy Visualization**: Kinetic and potential energy bars.
- 📤 **CSV Export**: Export angle-time graph data for Excel analysis.
- 🧪 **Manual Controls**: Adjust length, mass, and gravity with sliders and inputs.


---

## 📦 Files

- `index.html` – Main simulation (HTML, CSS, JS combined)
- `tick.wav` – Tick-tock sound on each peak
- `pendulum_graph_data.csv` – Generated on export (angle vs time)

---

## 🛠️ Controls

| Control   | Function                          |
|-----------|-----------------------------------|
| 📏 Length | Adjust string length              |
| 🌍 Gravity| Change gravitational acceleration |
| ⚪ Mass   | Visual size of the bob            |
| 🔄 Restart | Resets swing to initial state    |
| 📤 Export | Saves graph data as CSV           |

---

## 🧮 Equations Used

- **Time Period**:  
  `T = 2π√(L / g)`

- **Kinetic Energy**:  
  `KE = ½mv²`

- **Potential Energy**:  
  `PE = mgh`

- **Angular Displacement**:  
  `θ(t) ≈ θ₀ cos(√(g/L)·t)`

---

## 📊 Exporting Data

Click the **📤 Export Graph Data** button to save the simulation log (`Time vs Angle`) as a `.csv`. You can import this into:

- 📊 Microsoft Excel  
- 📈 Google Sheets  
- 📉 Python (Pandas, Matplotlib)  
- 📐 MATLAB

---

## 🔧 Setup Instructions

1. Clone or download the repo:
   ```bash
   git clone https://github.com/yourusername/pendulum-simulator.git
