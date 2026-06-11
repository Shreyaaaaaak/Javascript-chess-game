# ♟️ JavaScript Chess Game

> A fully interactive chess game built with vanilla HTML, CSS, and JavaScript — featuring neon glow animations, move highlighting, and turn-based gameplay.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-brightgreen?style=flat-square&logo=vercel)](https://javascript-chess-game-nine.vercel.app/)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**[→ Play it live](https://javascript-chess-game-nine.vercel.app/)**

---

## Overview

A complete two-player chess game running in the browser with no frameworks, no dependencies (except jQuery for DOM), and no backend. Built to showcase clean game logic and creative CSS animations.

---

## Features

- Full 8×8 chess board with all standard piece movements
- Click to select a piece — valid moves highlighted in green
- Neon glow animations on piece hover and selection
- Turn indicator — alternates White / Black after each move
- Piece shake animation on invalid move attempt
- Zero setup — open in browser and play instantly

---

## Live Demo

**[→ javascript-chess-game-nine.vercel.app](https://javascript-chess-game-nine.vercel.app/)**

---

## How to play

1. White moves first — click any white piece to select it
2. Green squares show valid moves
3. Click a highlighted square to move
4. Turn passes to Black — repeat
5. Capture the opponent's king to win

---

## Running locally

```bash
# Clone the repo
git clone https://github.com/Shreyaaaaaak/Javascript-chess-game.git
cd Javascript-chess-game

# Open in browser — no install needed
open index.html
```

---

## Project structure

```
Javascript-chess-game/
├── index.html    # Game board and layout
├── style.css     # Board styling, neon animations, transitions
├── script.js     # All chess logic — piece movement, turn handling
└── README.md
```

---

## Tech stack

- **HTML5** — board structure and piece layout
- **CSS3** — neon glow effects, hover transitions, shake animations
- **JavaScript** — move validation, turn logic, game state
- **jQuery 3.2.1** — DOM manipulation

---

## What I learned building this

- Implementing chess move validation from scratch (especially castling and en passant edge cases)
- Managing complex game state in vanilla JS without a framework
- CSS animation techniques for interactive feedback (glow, shake, highlight)

---

## Future improvements

- [ ] AI opponent (minimax algorithm)
- [ ] Check / checkmate detection with alerts
- [ ] Move history panel
- [ ] Timer mode for blitz chess
- [ ] Mobile touch support

---

## Built by

**Shreya Kaushik** — ECE @ KIIT University (2027)  
[GitHub](https://github.com/Shreyaaaaaak) · [LinkedIn](https://www.linkedin.com/in/shreyakaushik2308)

---

## License

MIT — free to fork and extend.
