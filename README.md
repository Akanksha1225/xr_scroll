# XR Gallery — Touchless Hand Control Image Gallery

A WebXR-inspired image gallery with touchless hand gesture controls using MediaPipe Hand Tracking.

🌐 **Live Demo**: [xr-scroll.vercel.app](https://xr-scroll.vercel.app/)  
📦 **GitHub**: [github.com/Akanksha1225/xr_scroll](https://github.com/Akanksha1225/xr_scroll)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Hand Tracking** | Real-time hand detection using MediaPipe Hands |
| **Virtual Cursor** | Custom cursor follows your index finger |
| **Pinch-to-Select** | Bring thumb and index finger together to click |
| **Edge Scrolling** | Move hand to screen edges to scroll |
| **3D Card Effects** | Hover tilt and selection bump animations |
| **Onboarding Modal** | Tutorial popup for first-time users |

---

## 🎮 Controls

| Gesture | Action |
|---------|--------|
| ☝️ **Point** | Move virtual cursor with index finger |
| 🤏 **Pinch** | Select/click items (thumb + index finger) |
| 👋 **Move to Edges** | Scroll gallery horizontally/vertically |

---

## 🛠️ Tech Stack

- **HTML5/CSS3/JavaScript** — No frameworks, pure vanilla
- **MediaPipe Hands** — Real-time hand tracking
- **Picsum Photos API** — High-quality stock images
- **CSS Animations** — 3D transforms and transitions

---

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/Akanksha1225/xr_scroll.git
cd xr_scroll

# Serve locally (any static server works)
python3 -m http.server 8080

# Open in browser
open http://localhost:8080
```

---

## 📁 Project Structure

```
xr_scroll/
├── index.html      # Single-page application
└── README.md       # This file
```

---

## 🎨 Design Features

- **Playful gradient background** with animated floating shapes
- **Glassmorphism cards** with blur effects
- **Cursor trail effect** for enhanced interactivity
- **Category sections**: Nature, Architecture, Travel, Abstract
- **Help button** to re-show onboarding tutorial

---

## 📸 Screenshots

The gallery features 4 themed sections with 10 images each:
- 🌿 **Nature** — Landscapes and wildlife
- 🏛️ **Architecture** — Buildings and structures
- ✈️ **Travel** — World destinations
- 🎨 **Abstract** — Artistic compositions

---

## 🔧 Configuration

Customize behavior in the `CONFIG` object:

```javascript
const CONFIG = {
  handTracking: {
    maxHands: 1,
    detectionConfidence: 0.7,
    trackingConfidence: 0.5
  },
  scrollSpeed: 8,
  pinchDistance: 50  // Threshold for pinch detection
};
```

---

## 📄 License

MIT License — Feel free to use and modify!

---

## 👤 Author

**Akanksha** — [GitHub](https://github.com/Akanksha1225)
