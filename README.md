# 🌍 Earth Satellite Debris Visualization

A stunning real-time 3D visualization of satellites and space debris orbiting Earth, built with Three.js and featuring authentic NASA imagery.

![Earth Satellite Visualization](https://img.shields.io/badge/Status-Active-brightgreen) ![Three.js](https://img.shields.io/badge/Three.js-r128-blue) ![NASA](https://img.shields.io/badge/Data-NASA-orange)

## ✨ Features

### 🛰️ **Satellite Tracking**
- **1000+ satellites** in accurate Low Earth Orbit (LEO) positions
- **Real orbital mechanics** with continuous satellite motion
- **Multiple satellite types**: Starlink, ISS, debris, weather satellites
- **Color-coded visualization** by orbital regime (LEO/MEO/GEO/HEO)

### 🌌 **Visual Excellence**
- **NASA 4K star map** backdrop with real stellar positions
- **Authentic Earth textures** from NASA Blue Marble project
- **Professional lighting** simulating sunlight in space
- **Smooth 60fps animation** with optimized rendering

### 🎮 **Interactive Controls**
- **Mouse navigation**: Drag to rotate, scroll to zoom
- **Keyboard shortcuts**: I/C/S/H/Esc for panel control
- **Background toggle**: NASA star field ↔ clean white analytical view
- **Satellite filtering** by type and orbital regime

### 🎨 **Customization**
- **Size control**: Satellite markers from 1-50 scale
- **Color customization**: Interactive pickers with preset options
- **Hideable UI panels** with smooth animations
- **Professional presentation mode**

## 🚀 Quick Start

### Prerequisites
- Modern web browser with WebGL support
- Local web server (for file loading)

### Installation

1. **Clone or download** the project files
2. **Add NASA star map**: Place `starmap_2020_4k.jpg` in the project directory
  - Download from: [NASA Scientific Visualization Studio](https://svs.gsfc.nasa.gov/4851/)
3. **Start a local server**:
  ```bash
  # Python
  python -m http.server 8000
  
  # Node.js
  npx serve .
  
  # VS Code Live Server extension
  Right-click index.html → "Open with Live Server"
