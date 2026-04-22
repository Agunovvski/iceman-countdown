# ICEMAN 🧊✨

> An interactive 3D countdown experience for Drake's album **ICEMAN**, releasing May 15, 2026.

## What's It Do?

A hyper-realistic 3D ice cube melts in real-time, revealing a golden core. The closer we get to release day, the more the ice melts — until on May 15th, the gold breaks free.

## Features

| Feature | Description |
|---------|-------------|
| **🧊 3D Ice Cube** | Physically-based rendering with custom ice refraction shaders |
| **🔥 Cursor Heat** | Hover over the ice to accelerate melting |
| **⚡ Click to Crack** | Click the cube to shatter the surface |
| **💛 Gold Reveal** | Gold core revealed progressively as ice melts |
| **🌊 Meltwater Pool** | Live water formation as cube shrinks |
| **❄️ Frost Overlay** | Canvas-based frost crystals that melt near your cursor |
| **✨ Chromatic Aberration** | Post-processing ice distortion at the edges |
| **⏳ Live Countdown** | Days/hours/minutes/seconds to release |
| **🎊 Release Celebration** | Gold flash + pulse animation on launch day |
| **🌀 Orbit Controls** | Drag to rotate, scroll to zoom, double-click to reset |

## Tech Stack

- **Three.js r160** — 3D rendering, PBR, post-processing (bloom, chromatic aberration)
- **Custom GLSL** — Ice refraction, melting physics, caustic light
- **GSAP-style animations** — CSS keyframes for UI glows

## Quick Start

```bash
# Clone
cd ~/documents/github/iceman-countdown

# Or just open directly
open index.html
```

Or serve it over a local server for best experience:
```bash
python3 -m http.server 3000
# open http://localhost:3000
```

## File Structure

```
iceman-countdown/
├── index.html          # 🚀 Everything. HTML + CSS + Three.js module
└── README.md           # This file
```

Single-file design — drop it on any static host (Vercel, Netlify, GitHub Pages) and it runs.

## Interactive Controls

| Action | Result |
|--------|--------|
| 🖱️ Hover on ice cube | Accelerated local melting |
| 🖱️ Click on ice cube | Spawn crack / fracture particles |
| 🖱️ Double-click anywhere | Reset camera orbit |
| 🖱️ Drag | Rotate camera around cube |
| 🖱️ Scroll | Zoom in/out |

## Roadmap

- [x] Ice cube with PBR & custom shaders
- [x] Countdown to May 15, 2026
- [x] Progressive melt + gold reveal
- [x] Frost overlay effect
- [x] Click-to-crack particles
- [x] Post-processing (bloom + chromatic aberration)
- [x] Release day celebration
- [ ] 🎙️ Audio-reactive ice (Web Audio API)
- [ ] 🔥 Microphone heat acceleration
- [ ] 🌐 Collective heat map / socket.io
- [ ] 📱 Device gyroscope interaction
- [ ] 📍 Milestone unlocks (teasers at 10/5/3 days)
- [ ] 🔑 Audio QR codes embedded in gold core visuals
- [ ] 🎵 Stream integration (Spotify/Apple Music embed)

## License

Fan project. Not affiliated with Drake or OVO Sound.
