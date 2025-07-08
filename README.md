# 🌌 3D Solar System Simulation – Three.js

This project is a fully interactive and responsive **3D simulation of the Solar System** built with **Three.js**. It demonstrates planetary orbits, self-rotation, realistic lighting, and user interactions — all powered by **pure JavaScript** with no CSS animations.

---

## 🚀 Features

### ✅ Core Requirements:
- 🌞 **Sun** placed at the **center** of the scene.
- 🪐 **All 8 planets (Mercury to Neptune)** orbiting the Sun.
- 🌍 **Each planet** has:
  - A 3D textured sphere.
  - Unique **default orbital** and **self-rotation speeds**.
- 🔭 **Realistic lighting** (point light from the Sun + ambient light).
- 🧭 **Perspective camera** and orbital controls.

### 🎛️ Speed Control Panel:
- 🎚️ Sliders provided for **each planet** to control its orbital speed in **real-time**.
- 🔄 Speed changes are applied instantly through interaction with the animation loop using **JavaScript** only.

---

## ✨ Bonus Features Implemented
- ✅ **Pause/Resume** button to toggle planetary motion.
- ✅ **Background stars** using cube textures.
- ✅ **Tooltips** on **hovering planets**, showing their names.
- ✅ Camera control using **OrbitControls** (mouse drag, zoom, pan).

---

## 📸 Preview

![Solar System Preview](./preview.png)  
*Real-time orbit animation with planet labels and control panel.*

---

## 🧩 Tech Stack

- **Three.js** (r127 via `unpkg`)
- **JavaScript** (ES6 modules)
- **HTML5** & DOM APIs
- **Texture Mapping** with `TextureLoader`
- **Raycasting** for hover tooltips
- **dat.GUI** for control panel

---

## 📂 Project Structure

