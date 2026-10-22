# Tiny Trails

Tiny Trails is a small 3D arcade hopping game made with Three.js for a bachelor "Game development" class. Guide a little traveler across busy roads and moving river logs, and try to beat your best distance.

> Main reference: Crossy Road

> Tool used: **Three.js**

**Authors (A-z):** /
[Name | GitHub user]
1. Andrew Húngaro | andrewhungaro42_design
2. Felipe Augusto | felipesaugusto
3. Vinícius F. | ViniFunt
4. Vinícius Machado | viniciusmachadovianna

## How to use

1. Install [Node.js](https://nodejs.org/).
2. Install the project dependencies with `npm install`.
3. Start the development server with `npm run dev`.
4. Open the local URL printed by Vite in your browser.

### Core mechanics

- **Movement:** Player hops one grid tile per key press (forward, back, left, right)
- **Map generation:** Procedurally generated rows, grass, road + cars and river + logs
- **Collisions:** Car hit, Jumping on water, get carried sideways on a log
- **Camera:** Follows player, staying behind for too long ends the game as well
- **Scoring:** Based on the furthest row reached, it is saved in `localStorage`

### Controls

- Arrow keys or WASD: hop forward, backward, left, or right.
- Use the sound button in the top-right corner to mute or enable hop sounds.

# Demonstrations and deploy

...
