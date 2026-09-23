# Bloom’s Taxonomy Interactive Prototype

Open `index.html` in a modern browser (Chrome, Edge, Safari, or Firefox).

## Prototype contents
- Challenge 1: Sort Bloom’s levels into LOTS and HOTS.
- Challenge 2: Build the Bloom’s Taxonomy pyramid with three attempts before explanatory feedback.
- Challenge 3: Match 18 action verbs to the six Bloom’s levels.
- “One more thing” teaching note and ILO transition.
- Keyboard/click alternative to drag-and-drop.
- Background music and sound effects with separate Music and SFX controls.

## Audio
Audio files are in `assets/audio/`:
- `background-music.mp3` — loops quietly after the learner presses Start.
- `select.mp3` — selecting or picking up a card.
- `drop.mp3` — successful placement.
- `check.mp3` — pressing Check.
- `success.mp3` — completing a challenge perfectly.

Browsers generally block audible autoplay, so background music begins only after the learner presses **Start activity**. Music and sound effects can be turned off independently from the controls at the top-right.

## Hosting
This is a static site. Upload the full folder structure to GitHub Pages or another static host. Keep `assets/audio/` beside `index.html` so the relative audio paths continue to work.
