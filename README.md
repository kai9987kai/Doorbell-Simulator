
# Doorbell Simulator

An interactive 3D **Universal Doorbell Lab** for simulating how different doorbell systems work.  
The project models electrical behaviour, mechanical movement, sound output, wiring faults, thermal load, diagnostics, and guided learning in one browser-based simulator.

![Doorbell Simulator](https://img.shields.io/badge/Project-Doorbell%20Simulator-blue)
![HTML](https://img.shields.io/badge/HTML-100%25-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

## Overview

**Doorbell Simulator** is a single-page educational web app that lets users explore doorbell circuits and mechanisms in a visual, hands-on way.

It is designed like a virtual electronics testbench where you can:

- Press a 3D doorbell button
- Change the doorbell mechanism
- Adjust voltage, wire length, wire material, and wire gauge
- Inject realistic faults
- View live diagnostic readings
- Hear generated doorbell sounds
- Learn how real technicians fault-find doorbell systems

The simulator is useful for education, electronics learning, demonstrations, prototyping, and experimenting with electromechanical systems safely in the browser.

---

## Features

### Interactive 3D Doorbell Lab

- Real-time 3D scene
- Clickable doorbell button
- Orbit-style camera controls
- Multiple camera viewpoints
- Component labels
- Circuit path view
- Mechanism view
- Push switch view
- Full bench view

### Doorbell Mechanisms

Choose between multiple simulated systems:

- Classic Solenoid / Ding-Dong
- Tubular Chimes / Westminster
- Vintage Trembler / Continuous Gong
- Mechanical Rotary Bell
- Heavy Industrial Siren
- Sleek Wireless Smart Cam
- Ultra-High Frequency Piezo

### Electrical Simulation

Adjust core circuit properties:

- Power source voltage
- Wire material
- Cable length
- Wire gauge / thickness
- Contact bounce
- Switch mode
- Load resistance
- Current draw
- Power usage
- Stored energy

### Fault Injection

Simulate common real-world problems:

- Healthy circuit
- Open circuit / broken wire
- Stuck closed button
- Short circuit bypassing the load
- Corroded terminals / voltage drop
- Mechanical jam / weak striker
- Weak battery / sag under load

### Diagnostics Panel

Built-in diagnostic tools include:

- Digital multimeter
- Probe circuit mode
- Live circuit map
- Diagnostic oscilloscope
- Thermal stress meter
- Coil / driver temperature
- Predicted SPL
- Event log
- Health forecast

### Audio Simulation

The simulator uses browser audio to generate doorbell sounds with:

- Adjustable pitch
- Volume control
- Stereo panning
- Reverb / delay
- Different sound profiles for different mechanisms
- Mute option
- Safer gain handling

### Learning Mode

Includes short educational explanations covering:

- What happens when the switch is pressed
- How current creates magnetic fields
- How solenoids and strikers work
- How to fault-find like a technician
- How to use voltage readings to locate faults

### Accessibility & Usability

- Keyboard shortcuts
- Reduced motion mode
- Mobile control panels
- Save setup button
- Reset lab button
- Labels toggle
- Touch-friendly controls
- Responsive layout

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Ring / activate the bell |
| `F` | Toggle flux field |
| `P` | Toggle probe mode |
| `L` | Toggle labels |
| `1` | Full bench view |
| `2` | Mechanism view |
| `3` | Push switch view |
| `4` | Circuit path view |

---

## How to Use

1. Open the simulator in a modern browser.
2. Choose a system preset or select your own doorbell mechanism.
3. Press the red doorbell button or press `Space`.
4. Adjust the electrical and mechanical controls.
5. Add a fault from the fault injection menu.
6. Use the diagnostic panel to inspect readings.
7. Enable **Probe Circuit** and click components to test them.
8. Read the Learn Mode notes to understand what is happening.

---

## Installation

No build tools are required.

```bash
git clone https://github.com/kai9987kai/Doorbell-Simulator.git
cd Doorbell-Simulator
````

Then open:

```bash
index.html
```

You can also serve it locally with a simple development server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## Requirements

A modern browser with support for:

* HTML5
* CSS3
* JavaScript modules
* WebGL
* Web Audio API

The project uses Three.js through a CDN import map, so an internet connection may be needed when running the page unless the dependency is downloaded locally.

---

## Project Structure

```text
Doorbell-Simulator/
├── index.html          # Main simulator app
├── README.md           # Project documentation
├── LICENSE             # MIT license
├── SECURITY.md         # Security policy
└── CODE_OF_CONDUCT.md  # Community guidelines
```

---

## Technology Used

* HTML
* CSS
* JavaScript
* Three.js
* WebGL
* Web Audio API
* Canvas-based diagnostic displays

---

## Educational Use Cases

This simulator can help with:

* Learning basic circuits
* Understanding switches and loads
* Demonstrating solenoid behaviour
* Explaining voltage drop
* Showing how wire resistance affects performance
* Teaching fault-finding methods
* Comparing mechanical and smart doorbell systems
* Visualising current, power, heat, and sound output

---

## Ideas for Future Improvements

Possible future upgrades:

* Export diagnostic reports
* Add wiring diagram presets
* Add transformer simulation
* Add battery discharge graphs
* Add relay and smart-doorbell modules
* Add multiplayer classroom mode
* Add guided repair challenges
* Add scoring for fault-finding exercises
* Add downloadable screenshots
* Add offline Three.js bundle

---

## Safety Note

This is a browser-based educational simulator.
It should not be used as a replacement for qualified electrical advice when working on real wiring, mains-powered transformers, or installed doorbell systems.

Always isolate power before working on real circuits.

---

## License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

## Author

Created by **Kai Piper**.

GitHub: [@kai9987kai](https://github.com/kai9987kai)

```
::contentReference[oaicite:1]{index=1}
```

[1]: https://raw.githubusercontent.com/kai9987kai/Doorbell-Simulator/main/README.md "raw.githubusercontent.com"
