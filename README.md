# SNAKE — Classic Edition

A modern, minimal, and elegant implementation of the classic Snake arcade game built entirely from scratch with vanilla HTML5, CSS3, and JavaScript in a single self-contained file.

---

## 🎮 How to Play

### Controls
| Key / Input | Action |
| :--- | :--- |
| <kbd>Space</kbd> or **Play** button | Start game from main menu |
| <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> or <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> | Control snake direction |
| <kbd>P</kbd> or **Pause** button | Pause / resume gameplay |
| <kbd>C</kbd> | Restart immediately after Game Over |
| <kbd>Q</kbd> | Return to Main Menu |
| <kbd>Esc</kbd> | Close Settings or How to Play overlay |
| **Touch / Mobile** | Swipe on the board or use on-screen D-Pad |

### Objective & Rules
- Eat the food items (+10 points each) to grow longer and increase your score.
- Avoid colliding with outer boundary walls and your own tail.
- Input queue buffering prevents accidental 180° self-collisions.

---

## ✨ Features

- **3 Dynamic Progression Levels**:
  - **Level 1**: Starting deliberate pace.
  - **Level 2**: Unlocks automatically at **100 points** (faster movement).
  - **Level 3**: Unlocks automatically at **200 points** (arcade challenge).
- **HUD & Score Tracking**: Real-time display of current score, food eaten, active level, and high score.
- **Persistent High Scores**: High scores and user preferences persist across browser sessions using `localStorage`.
- **Pause & Resume**: Clean paused overlay keeping the game board visible without timer distortion.
- **Settings & Accessibility**:
  - Sound effects toggle.
  - Reduced Motion mode (disables screen shake and particle bursts).
  - Base speed multiplier (Relaxed 0.8x, Standard 1.0x, Fast 1.2x).
  - On-screen touch D-Pad toggle.
- **Zero-Dependency Audio Synthesizer**: Procedural sound effects using Web Audio API oscillators (no external MP3/WAV files required).
- **Mobile & Touch Friendly**: Fully responsive layout, touch swipe gestures, and tactile on-screen D-Pad.

---

## 🚀 How to Run

No installations, node packages, or servers required:

1. Download or clone this repository.
2. Open `snake-game.html` (or `index.html`) in any modern web browser (Edge, Chrome, Firefox, Safari).
3. Press <kbd>Space</kbd> or click **Play Game** and enjoy!
