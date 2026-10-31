# Apex Grand Prix (Car-Race) 🏎️💨

A polished, retro-style 2D top-down arcade racing game built as a single, self-contained HTML5 file with zero external dependencies, libraries, or asset downloads.

Playable directly in modern desktop and mobile web browsers by opening `index.html`.

![Apex Grand Prix Banner](https://img.shields.io/badge/Status-Fully%20Playable-brightgreen?style=for-the-badge)
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-orange?style=for-the-badge&logo=html5)
![Vanilla JS](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge)

---

## 🎮 Features

- **4-Car Grand Prix**: Race your blue machine against 3 distinctive AI opponents (Blaze, Apex, and Viper) with adaptive racing lines, speed management, and overtaking behavior.
- **Arcade Vehicle Physics**: Gradual acceleration, braking, reverse gear, momentum, speed-dependent steering, and lateral drift dynamics.
- **Dynamic Drifting**: Controlled power-slides on corners with realistic tire skid marks and smoke particle effects.
- **Track Surface Mechanics**:
  - **Asphalt Road**: Maximum grip and top racing speed.
  - **Striped Curbs**: Slight loss of grip and curbside rumble.
  - **Grass Off-Road**: Heavy drag, capped top speed, and dust trails to penalize shortcutting.
  - **Track Barriers**: Collision rebound with spark effects and velocity dampening.
- **Boost Pads**: Strategically positioned boost zones granting instant acceleration and speed bursts with visual flames.
- **Sequential Checkpoint Validation**: 24 checkpoints ensure honest lap tracking without track cutting.
- **Synthesized Web Audio**: 100% procedurally synthesized engine rumble, tire squeals, countdown beeps, boost whoosh, and victory fanfares using the Web Audio API.
- **Responsive & Touch Friendly**:
  - Desktop keyboard controls (`WASD` / Arrow keys).
  - Virtual multi-touch controls for mobile and tablet devices.
  - Fullscreen toggle and pause system (`P` / `Esc`).
- **Race HUD & Radar**: Real-time position tracking, live lap timer, best lap persistence (`localStorage`), speedometer gauge, boost meter, and live minimap radar.

---

## 🏁 Controls

### Desktop Controls
| Action | Key |
|---|---|
| **Accelerate** | `W` or `↑` (Up Arrow) |
| **Brake / Reverse** | `S` or `↓` (Down Arrow) |
| **Steer Left** | `A` or `←` (Left Arrow) |
| **Steer Right** | `D` or `→` (Right Arrow) |
| **Start Race** | `Space` |
| **Pause / Unpause** | `P` or `Esc` |
| **Restart Race** | `R` |

### Mobile / Touch Controls
- **Left Side**: Virtual buttons for **Steer Left** and **Steer Right**.
- **Right Side**: Virtual buttons for **Gas** (Accelerate) and **Brake / Reverse**.
- Supports simultaneous multi-touch steering and throttle.

---

## 🚀 Getting Started

No build steps, node modules, or web servers required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/03DxD12/Car-Race.git
   ```
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Press **Start Race** or hit `Space` to start your engine!

---

## 📜 License

This project is open-source and licensed under the [MIT License](LICENSE).
