# 🪐 ORBIT — Explore the Solar System in 3D

### A journey through our solar system, from the surface of distant planets to the edge of a black hole.

**ORBIT** is an interactive, browser-based 3D space exploration experience designed to bring the wonders of our universe closer to everyone.

Travel between planets, explore NASA-derived planetary imagery, witness an illustrative supernova, and experiment with gravitational time dilation near a black hole — all from your browser.

**🌐 [Explore ORBIT Live](https://dev-orbit-explorer.funsiren128.chatgpt.site/)**

---

## 🌌 About the Project

Space is extraordinary, but understanding its scale, beauty, and physics through textbooks and static images can be difficult.

ORBIT transforms those concepts into an immersive, interactive experience.

Rather than simply displaying information about the solar system, ORBIT lets users explore celestial objects in three dimensions, observe their movement, and interact with visualizations inspired by real astrophysics.

The project combines **3D graphics, astronomy, mathematics, and interactive web development**.

## ✨ Features

### 🪐 1. Interactive Solar System
- Explore all eight planets, from Mercury to Neptune.
- Zoom in to examine planetary surfaces.
- Rotate and navigate through the 3D environment.
- Observe planetary rotation and orbital motion.
- Switch between individual planets and the entire solar system.
- Explore the Sun with enhanced visual effects.

### ☀️ 2. Immersive Space Environment
- Detailed planetary textures derived from astronomical imagery.
- Atmospheric and lighting effects.
- A surrounding starfield.
- Interactive camera navigation.
- Adjustable animation speed.
- Optional orbital path visualization.

### 💥 3. Supernova Simulation
Explore an artistic visualization of one of the universe's most energetic events.

- Observe a stylized stellar explosion.
- Watch expanding material and visual effects.
- Replay the explosion.
- Learn about the final stages of massive stars.

*Scientific note: The simulation is illustrative rather than a physically exact supernova model. Our Sun is not massive enough to undergo a core-collapse supernova.*

### 🕳️ 4. Black Hole & Relativity Lab

Go beyond the solar system and explore the fascinating physics of black holes.

**Gravitational Lensing**

Explore a visualization of how a black hole bends light, distorting the surrounding environment.

**Gravitational Time Dilation**

Experiment with how gravity changes the passage of time.

For a stationary observer outside a non-rotating Schwarzschild black hole:

$$
\frac{d\tau}{dt}=\sqrt{1-\frac{R_s}{r}}
$$

Where:
- $\tau$ = proper time experienced near the black hole
- $t$ = time measured by a distant observer
- $R_s$ = Schwarzschild radius
- $r$ = radial position of the observer

Move the simulated probe closer to the event horizon and observe how its clock slows relative to a distant clock.

The black-hole lab includes numerical light-ray integration alongside illustrative accretion-disk rendering.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Responsive interface and visual styling |
| JavaScript | Interactions, animations, and simulation logic |
| Three.js | 3D rendering and scene management |
| WebGL | GPU-accelerated graphics |
| Mathematical Models | Orbital approximations and relativity calculations |

## 🎮 How to Explore

| Action | Control |
|---|---|
| Rotate camera | Click and drag |
| Zoom | Mouse scroll / trackpad pinch |
| Visit a planet | Select it from the navigation bar |
| Explore whole system | Solar System / Home |
| Adjust animation speed | Time slider |
| Pause motion | Pause button |
| Explore stellar explosion | Supernova |
| Explore black-hole physics | Black Hole |

## 🚀 Getting Started

### Option 1: Explore Online

Visit the live website:

**https://dev-orbit-explorer.funsiren128.chatgpt.site/**

No installation required.

### Option 2: Run Locally

Clone the repository (replace `YOUR-REPOSITORY` with the actual repository name):

```bash
git clone https://github.com/dnain5090/YOUR-REPOSITORY.git
```

Navigate into the project:

```bash
cd YOUR-REPOSITORY
```

Start a local server for the original multi-file source:

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

The standalone HTML build can also be opened directly in a compatible browser without starting a local server.

### Option 3: Deploy Using GitHub Pages

1. Upload the project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` and `/ (root)`.
5. Save your settings.

Once published, GitHub Pages provides a public website address, typically `https://dnain5090.github.io/YOUR-REPOSITORY/`.

---

## 🔬 Scientific Accuracy & Limitations

ORBIT aims to make astronomy engaging while distinguishing mathematical models from artistic visualizations.

- Planetary textures are based on astronomical imagery and processed surface maps.
- Planet sizes and orbital distances are compressed for easier navigation.
- Planetary positions and orbital paths are illustrative rather than real-time ephemerides.
- Supernova effects are artistic visualizations.
- The black-hole clock model applies to stationary observers outside a non-rotating Schwarzschild black hole.
- Black-hole light bending is numerically approximated; the accretion disk is illustrative.
- The experience is educational and is not intended to replace professional astronomical simulation software.

## 📚 References & Credits

This project draws inspiration and scientific information from:

- [NASA Solar System Exploration](https://science.nasa.gov/solar-system/)
- [NASA — Black Hole Visualization](https://www.nasa.gov/universe/nasa-visualization-shows-a-black-holes-warped-world/)
- [NASA — The Sun](https://science.nasa.gov/sun/)
- [Solar System Scope — Planetary Textures](https://www.solarsystemscope.com/textures/)
- [Three.js](https://threejs.org/)

Planetary maps are sourced from **Solar System Scope / INOVE**, based on NASA imagery and elevation data, and are credited under **Creative Commons Attribution 4.0 (CC BY 4.0)**.

## 🌠 Project Vision

The goal of ORBIT is simple:

**Make exploring the universe feel less like reading a textbook and more like traveling through space.**

By combining computer graphics with astronomy and mathematical models, ORBIT demonstrates how interactive technology can make complex scientific concepts easier to visualize and understand.

This project is an exploration of the intersection between **computer science, physics, mathematics, and visual computing**.

---

*Built for curiosity. Inspired by the universe.*

**ORBIT — A little closer to the infinite.** ✨
