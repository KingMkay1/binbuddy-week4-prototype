# BinBuddy — Week 4 Build

A responsive, mobile-first waste-sorting assistant prototype.

## Files
- `index.html`: interface
- `style.css`: responsive styling
- `script.js`: item lookup and disposal instructions
- `BinBuddy_LoFi_Prototype.pdf`: low-fidelity wireframe and design rationale

## Research-informed decisions
- Plain-language item lookup for unfamiliar waste items.
- Visual category cues and direct bin recommendations.
- Special warning for batteries.
- Explicit reminder to check the building's own bin labels.
- Unknown items get a cautious response rather than a guessed bin.

## Limitations
This is an educational front-end prototype with a small manually maintained item list. It does not connect to a live municipal database or guarantee every local collection rule. Local authority guidance and the building's own signs take priority.

## Run
Open `index.html` in a modern browser; no build tools are required.

## Deploy on GitHub Pages
Create a new repository (suggested name: `binbuddy-week4-prototype`), upload these files to the repository root, then open Settings → Pages → Deploy from a branch → `main` → `/(root)`.
