<p align="center">
  <a href="https://bfusion-e.github.io/Tic--tac-toe-game/">
    <img src="https://img.shields.io/badge/%F0%9F%8E%AE_PLAY_GAME-CLICK_TO_PLAY-7C3AED?style=for-the-badge&labelColor=111827" alt="🎮 PLAY GAME — click to play">
  </a>
</p>

<h1 align="center">Neon Tic Tac Toe</h1>

<p align="center">A vibrant, lightweight Tic Tac Toe game built with HTML, CSS, and vanilla JavaScript. Play a friend locally or challenge the computer across three difficulty levels—right in your browser.</p>

## ✨ Features

- **Two game modes:** Play against the computer or take turns in local 2-player mode.
- **Three AI difficulties:** Easy (random legal moves), Medium (wins, blocks, and positional play), and Impossible (optimal Minimax; the AI cannot lose).
- **Complete game rules:** Alternating turns, all eight winning lines, draws, highlighted winning tiles, and win/draw animations with confetti.
- **Match controls:** Restart a round without losing scores, or start a new match to reset scores and history.
- **Player names and scoreboard:** Separate scores for X, O, and draws.
- **Match history and statistics:** Recent results, games played, and win rate are saved locally in the browser.
- **Personalization:** Dark and light themes, generated sound effects with a mute toggle, and responsive layouts.
- **Accessibility:** Keyboard-operable buttons, visible focus indicators, live status updates, descriptive board labels, and reduced-motion support.
- **Lightweight by design:** No frameworks, backend, paid APIs, or build step. The game and styling are self-contained in `index.html`.

## 🎯 How to play

Choose **vs Computer** or **2 Players**, then click or tap an empty square. X starts. Get three marks in a row horizontally, vertically, or diagonally to win. If all squares are filled and nobody has three in a row, the round is a draw.

## 🖼️ Screenshots

Screenshots are not included yet. [Open the live game](https://bfusion-e.github.io/Tic--tac-toe-game/) to see the neon board and play in your browser.

## 🛠️ Technologies

- **HTML5** for the game structure
- **CSS3** for responsive styling, themes, animations, and visual effects
- **Vanilla JavaScript** for gameplay, AI opponents, scores, and local browser storage
- **GitHub Pages** for deployment

## 🚀 Run locally

Open [`index.html`](index.html) in a modern browser. No installation or build step is needed.

## 🌐 GitHub Pages

This game is published at **[bfusion-e.github.io/Tic--tac-toe-game](https://bfusion-e.github.io/Tic--tac-toe-game/)**. To deploy your own copy, enable GitHub Pages in **Settings → Pages**, select **Deploy from a branch**, and choose the `main` branch and `/ (root)` folder. GitHub serves `index.html` directly; no workflow or compilation is required.

## 🔒 Data and privacy

Scores, recent match history, theme, and sound preference are stored in your browser's `localStorage`; they are not sent to a server. Clearing browser storage resets locally saved settings and match history.
