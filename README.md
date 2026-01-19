# Pool 8 Ball Game

A classic Pool 8 Ball game built with HTML5 and WebAssembly using the Construct 3 engine.

## Overview

This is an interactive 8 Ball Pool game featuring physics-based gameplay powered by Box2D physics engine compiled to WebAssembly.

## Getting Started

### Running Locally

To run the game on your local machine:

```bash
cd "Pool 8 Ball html5"
python3 -m http.server 8000
```

Then open your browser and navigate to:
```
http://localhost:8000
```

### Project Structure

- **index.html** - Main game entry point
- **style.css** - Game styling
- **scripts/** - JavaScript runtime and game logic
  - `c3runtime.js` - Construct 3 runtime engine
  - `main.js` - Game initialization
  - `register-sw.js` - Service worker registration
- **icons/** - Game icons and favicon assets
- **images/** - Game graphics and sprites
- **media/** - Audio and video assets
- **box2d.wasm.js** - Box2D physics engine (WebAssembly)
- **opus.wasm.js** - Opus audio codec (WebAssembly)
- **sw.js** - Service worker for offline support
- **appmanifest.json** - Web app manifest
- **offline.json** - Offline support configuration

## Features

- Physics-based pool ball simulation
- Offline support via Service Worker
- Progressive Web App capabilities
- WebAssembly-powered performance

## Browser Requirements

- Modern browser with WebAssembly support
- JavaScript enabled
- Service Worker support (for offline play)

## Technical Stack

- **Engine:** Construct 3
- **Physics:** Box2D (WebAssembly)
- **Audio:** Opus codec (WebAssembly)
- **Platform:** HTML5/Web

## License

© 2026 Goomza Games. All rights reserved.
