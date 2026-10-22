# jogo
Three.js game for bachelor "Game development" class

**Authors (A-z):** /
[Name | GitHub user]
1. Andrew Húngaro | andrewhungaro42_design
2. Felipe Augusto | felipesaugusto
3. Vinícius F. | ViniFunt
4. Vinícius Machado | viniciusmachadovianna

## How to use
1. 


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