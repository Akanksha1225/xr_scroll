# XR Hand Control Web App

An immersive hand-tracking web application that enables touchless navigation through image galleries using MediaPipe hand detection.

## Features

- **Hand Tracking**: Uses MediaPipe Hands for real-time hand detection
- **Virtual Cursor**: Custom XR cursor that follows your index finger
- **Gesture Controls**:
  - Move hand to edge zones to scroll (vertical & horizontal)
  - Hover over items to slow down scrolling
  - Pinch gesture (thumb + index) to select items
- **Image Gallery**: Multiple carousel categories with dynamic images from Picsum Photos
- **Visual Feedback**: 
  - Camera HUD showing hand skeleton
  - Toast notifications on selection
  - Hover effects and animations

## Usage

1. Open `index.html` in a modern web browser (Chrome recommended)
2. Allow camera access when prompted
3. Move your hand in front of the camera:
   - **Move cursor**: Point with your index finger
   - **Scroll**: Move hand to screen edges
   - **Select**: Pinch thumb and index finger together

## Controls

| Gesture | Action |
|---------|--------|
| Index finger pointing | Move cursor |
| Hand near top/bottom | Scroll up/down |
| Hand near left/right | Pan carousels left/right |
| Pinch (thumb + index) | Click/Select item |
| Hover on card | Slow down horizontal scroll |

## Technologies

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) - Hand tracking
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [Picsum Photos](https://picsum.photos/) - Dynamic images

## Requirements

- Modern web browser with WebGL support
- Webcam access
- HTTPS or localhost (for camera access)

## License

MIT License
