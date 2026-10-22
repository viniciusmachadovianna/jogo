# Tiny Trails

Tiny Trails is a small 3D arcade hopping game made with Three.js for a bachelor "Game development" class. Guide a little traveler across busy roads and moving river logs, and try to beat your best distance.

**Authors (A-z):** /
[Name | GitHub user]
1. Andrew Húngaro | andrewhungaro42_design
2. Felipe Augusto | felipesaugusto
3. Vinícius F. | ViniFunt
4. Vinícius Machado | viniciusmachadovianna

### How to use

1. Install [Node.js](https://nodejs.org/).
2. Install the project dependencies with `npm install`.
3. Start the development server with `npm run dev`.
4. Open the local URL printed by Vite in your browser.

Run `npm run build` to create a production build in `dist/`.

### Controls

- Arrow keys or WASD: hop forward, backward, left, or right.
- On touch screens: swipe, tap the direction buttons, or use the on-screen
  controls.
- Use the sound button in the top-right corner to mute or enable hop sounds.

## Schedule
[Week | Goal]
1 | Cube hopping on a grid, orthographic camera, repo and roles
2 | Row generation, cars, collisions, game over
3 | Logs/water, menu, restart, score, sound
4 | Theme, characters, unique mechanic, polish, performance
5 | README, GIFs, GitHub Pages deploy

## Core mechanics

- Player hops one grid tile per key press (forward, back, left, right), with a short hop animation
- Procedurally generated rows: grass, road (cars), river (logs), maybe train tracks
- Collision: car hit = game over; water without a log = game over; riding a log carries you sideways
- Camera follows forward progress; falling too far behind ends the game
- Score = furthest row reached; best score saved in `localStorage`

## Tools
Three.js - https://threejs.org/

## Main reference
- Crossy Road