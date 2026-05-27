Saturn Particle Gesture — Aevai

Overview
---
This project is a browser-based interactive space visualization that renders a Saturn-like planet formed by dynamic particle systems and controlled via real-time hand gesture recognition using the webcam.

Features
---
- 3000+ particle system with core and ring particles
- Starfield background with parallax
- MediaPipe Hands integration for real-time gestures (open hand, fist, hand movement)
- Canvas-based rendering with multi-layer glow effects
- Responsive UI with small mirrored camera preview

How to run
---
1. Serve the directory over HTTP (required for webcam). For example, using Python 3:

```cmd
python -m http.server 8080
```

2. Open your browser to: `http://localhost:8080` and allow camera permission.

Notes & Troubleshooting
---
- The app uses MediaPipe Hands via CDN. If the model fails to load, check network connectivity and browser console.
- If webcam permission is denied, the preview will not start and hand tracking will be disabled.
- Mobile devices may reduce particle count for performance.

Keyboard
---
- `T` toggle hand tracking
- `I` toggle instructions

Files
---
- `index.html` — main page
- `styles.css` — UI styling
- `app.js` — application logic and rendering

License
---
MIT — feel free to adapt.
