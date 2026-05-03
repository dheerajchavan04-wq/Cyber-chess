
readme_content = """# ♟️ Cyber Chess | Science Fiction Chess

A futuristic, neon-themed chess game built with pure HTML, CSS, and JavaScript. No external dependencies required — just open the file in any modern browser and play!

![Theme](https://img.shields.io/badge/theme-cyberpunk-black?style=flat-square&color=00ffff)
![Tech](https://img.shields.io/badge/tech-vanilla--js-black?style=flat-square&color=9333ea)

---

## 🚀 Live Demo

**Deploy to Vercel in one click:**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/cyber-chess)

Or run locally:

```bash
git clone https://github.com/yourusername/cyber-chess.git
cd cyber-chess
# Just open index.html in your browser — no server needed!
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## ✨ Features

### 🎨 Cyberpunk Visual Design
- Deep black background with **cyan & purple neon glow effects**
- Animated gradient title with pulsing glow
- Subtle grid overlay and CRT scanline effects
- Glassmorphism UI panels with backdrop blur
- Responsive neon button hover animations

### 📋 Game Modes
| Mode | Description |
|------|-------------|
| **📖 Tutorial Mode** | Learn chess basics with guided play |
| **🎯 Range Mode** | Extended attack ranges — pieces influence distant squares |
| **🤖 AI Battle** | Face the computer with 3 difficulty levels |
| &nbsp;&nbsp;&nbsp;&nbsp;├─ Easy (1 Level) | Beginner-friendly AI |
| &nbsp;&nbsp;&nbsp;&nbsp;├─ Medium (3 Levels) | Intermediate challenge |
| &nbsp;&nbsp;&nbsp;&nbsp;└─ Hard (5 Levels) | Advanced AI opponent |
| **👥 Two-Player Battle** | Local hotseat multiplayer |

### ♟️ Chessboard
- Initially hidden; appears after mode selection
- **Animated piece movements** with scale & glow effects
- **Valid move indicators**: cyan dots (moves), purple highlight (captures)
- **Coordinate labels** (a-h, 1-8) on the board edges
- **Active player indicators** with pulsing neon glow
- **Move history** display in standard algebraic notation

### 🎮 Control Panel
| Button | Action |
|--------|--------|
| 🔄 Restart | Reset the board to starting position |
| ↩️ Undo | Revert the last move |
| 💡 Hint | Get a suggested valid move |

### ⬆️ Pawn Promotion
- Elegant overlay panel when a pawn reaches the last rank
- Choose: **Queen**, **Rook**, **Bishop**, or **Knight**
- Smooth pop-in animation with neon border glow

### 📱 Responsive Design
- Fully adapts to mobile, tablet, and desktop screens
- Scaled piece sizes for small displays
- Single-column layout on narrow viewports
- Touch-friendly tap targets

---

## 🏗️ Project Structure

```
cyber-chess/
├── index.html          # Complete game (HTML + CSS + JS in one file)
└── README.md           # This file
```

> **Note:** The entire game is contained in a single HTML file for maximum portability. No external assets, no build tools, no package manager needed.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure |
| **CSS3** | Neon styling, animations, responsive layout |
| **Vanilla JavaScript** | Game logic, piece movement, AI, event handling |
| **Unicode Chess Symbols** | ♔ ♕ ♖ ♗ ♘ ♙ ♚ ♛ ♜ ♝ ♞ ♟ |

---

## 🎯 Game Rules Implemented

- ✅ All standard chess piece movements
- ✅ Pawn forward moves, double-step from start, diagonal captures
- ✅ Knight L-shaped jumps
- ✅ Bishop diagonal sliding
- ✅ Rook horizontal/vertical sliding
- ✅ Queen combined movement
- ✅ King single-step movement
- ✅ Pawn promotion (auto-triggered overlay)
- ✅ Move history tracking
- ✅ Turn switching (White → Black)
- ✅ Undo last move

---

## 🚀 Future Enhancements

- [ ] Full AI opponent with minimax algorithm
- [ ] Check / Checkmate / Stalemate detection
- [ ] Castling (king-side & queen-side)
- [ ] En passant capture
- [ ] Move timer / blitz mode
- [ ] Sound effects & background music
- [ ] Save / load game state
- [ ] Online multiplayer via WebSocket

---

## 🙏 Credits

Built with 💜 and 💙 neon lights. Chess piece symbols via Unicode.

---

*"In the neon-lit future, every move is calculated."* ⚡
"""

with open('/mnt/agents/output/README.md', 'w', encoding='utf-8') as f:
    f.write(readme_content)

print("README.md saved successfully!")
