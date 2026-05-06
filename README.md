# Quantum Core Runner | Neural Drift

A browser-based 3D HTML game powered by Three.js and Mediapipe face mesh tracking.

## Overview

Quantum Core Runner is a futuristic reflex game where you control a glowing core through a neon tunnel using your head tilt and blink gestures. The game features:

- Real-time head tilt control using Mediapipe face mesh
- Dynamic speed scaling and obstacle avoidance
- Cyberpunk glassmorphism UI with countdown and game over screens
- Camera status feedback and blink-based menu selection

## How to Run

### Option 1: Open locally in your browser

1. Clone or download this repository.
2. Open `Tackingboal - Copy.html` in a modern browser.
3. Allow camera access when prompted.
4. Use head tilt left/right to move between lanes.
5. Blink twice to start the game or confirm menu options.

> Note: The game uses camera-based face tracking, so a browser with WebRTC camera support is required.

### Option 2: Run with a simple local server (recommended)

1. Open a terminal in this repository folder.
2. Start a simple HTTP server.

For Python 3:

```bash
python -m http.server 8000
```

For Node.js with `http-server`:

```bash
npx http-server . -p 8000
```

3. Open your browser and visit:

```text
http://localhost:8000/Tackingboal%20-%20Copy.html
```

4. Allow camera access and enjoy the game.

## Instructions

- `tilt left` or `tilt right` with your head to switch lanes
- `blink twice` to start the game from the title screen
- `avoid obstacles` that appear in each lane
- when the game ends, move your head left/right to select `Reboot System` or `Disconnect`
- `blink twice` again to confirm the selected menu option

## Advantages

- No installation required: runs directly in the browser.
- Uses advanced face tracking for intuitive hands-free control.
- Smooth 3D visuals with ambient fog, glowing effects, and motion blur.
- Fast to launch and easy to test using a local server.
- Built with open web standards: HTML, CSS, JavaScript, Three.js, and Mediapipe.

## Tips

- Use a well-lit environment for better face tracking.
- Keep your face centered in the camera view.
- If the camera fails to initialize, refresh and allow permissions again.

## Files

- `Tackingboal - Copy.html` — main game file
- `README.md` — project overview, usage instructions, and advantages
