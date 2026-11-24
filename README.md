# Neon Tic Tac Toe

A complete, lightweight Tic Tac Toe game built with plain HTML, CSS, and vanilla JavaScript. Play against a friend locally or challenge the computer across three difficulty levels—all in a responsive neon-themed interface.

## Play

Open [`index.html`](index.html) in a modern browser, or publish the repository with GitHub Pages.

## Features

- **Two game modes:** Player vs Computer and local 2-player.
- **Three AI levels:** Easy (random legal moves), Medium (wins, blocks, and positional play), and Impossible (optimal Minimax; the AI cannot lose).
- **Complete game rules:** Alternating turns, all eight winning lines, draws, highlighted winning tiles, and win/draw animations with confetti.
- **Match controls:** Restart a round without losing scores, or start a new match to reset scores and history.
- **Player names and scoreboard:** Separate scores for X, O, and draws.
- **Match history and statistics:** Recent results, games played, and win rate are saved locally in the browser.
- **Dark and light themes**, generated sound effects with a mute toggle, and responsive layouts.
- **Accessibility touches:** Keyboard-operable buttons, visible focus indicators, live status updates, descriptive board labels, and reduced-motion support.
- **No frameworks, backend, paid APIs, or build step.** The game and its styling are self-contained in `index.html`. Google Fonts are an optional visual enhancement; system fallbacks work offline.

## How to play

Choose **vs Computer** or **2 Players**, then tap or click an empty square. X starts. The first player to place three marks in a row horizontally, vertically, or diagonally wins. A full board with no winning line is a draw. Change the computer difficulty from **Game setup**. Use **Restart game** to replay while keeping the match score, or **New match** to reset scores and history.

## GitHub Pages deployment

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder, then save.
4. After the deployment finishes, open the Pages URL shown in the Pages settings. GitHub serves `index.html` from the repository root.

No workflow or compilation is required. Changes pushed to the selected branch are published automatically.

## Data and privacy

Scores, recent match history, theme, and sound preference are stored in the browser's `localStorage`; they are not sent to a server. Clearing browser storage resets locally saved settings and match data.
