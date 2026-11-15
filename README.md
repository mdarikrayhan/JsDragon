# JsDragon

A small browser game written in plain JavaScript, HTML and CSS in June 2022. A dragon keeps running in from the right and you jump over it. Every dragon you clear adds a point and makes the next one a little faster. Background music plays while you play, and a sound plays on game over.

**Play it:** https://mdarikrayhan.github.io/JsDragon/

## How to play

| Key | Action |
| --- | --- |
| Up arrow | Jump |
| Left arrow / Right arrow | Move left or right |

The score is shown in the top-right corner. If the dragon hits you, the game stops. Reload the page to play again.

## Features

- Collision detection and scoring run on a 10 ms loop in [script.js](script.js).
- The dragon's animation gets 0.1 s shorter after every point, so the game speeds up as you go.
- The jump and the dragon's run are CSS keyframe animations in [style.css](style.css).
- Background music starts one second after the page loads ([music.mp3](music.mp3)), and [gameover.mp3](gameover.mp3) plays when you are hit.

## Tech stack

- HTML, CSS and JavaScript, with no libraries or build step
- Google Fonts (Ubuntu)

## Getting started

Open [index.html](index.html) in a browser, or play the hosted version on GitHub Pages at the link above.

## Project structure

```
index.html     page and game elements
script.js      controls, collision detection and scoring
style.css      layout and animations
bg.png         background image
dino.png       player character
dragon.png     obstacle
music.mp3      background music
gameover.mp3   game-over sound
```

## Author

Md Arik Rayhan — [mdarikrayhan.com](https://mdarikrayhan.com)
