# Pixel Valentine ❤️

A retro, pixel-art style interactive web application designed to playfully ask someone to be your Valentine. Built using HTML5, CSS3, and Vanilla JavaScript with a nostalgic Game Boy aesthetic.



## Features

* **Pixel Art Aesthetic**: Entirely CSS-driven pixel graphics (no external images required).
* **Persistent "No" Button**: The "No" button teleports randomly within the container whenever the user hovers over it or clicks it, making it nearly impossible to select.
* **Dynamic UI**: The "Yes" button grows larger every time the "No" button is missed, playfuly encouraging a "Yes" answer.
* **Retro Messages**: Randomized humorous messages appear when the "No" button is targeted.
* **Celebration Mode**: A "Win" screen featuring a glowing, animated pixel heart and falling mini-hearts upon selection.

## Tech Stack

* **HTML5**: Structure and content.
* **CSS3**: Styling, animations, and pixel art using `box-shadow` techniques.
* **Vanilla JavaScript**: Game logic, button movement, and DOM manipulation.

## How to Run

1.  Clone this repository or download the files.
2.  Open `index.html` in your web browser.
3.  Alternatively, view the live demo hosted on GitHub Pages: `[Insert Your GitHub Pages Link Here]`

## Engineering Notes

* **Pixelation**: Used `image-rendering: pixelated;` to ensure sharp edges on high-resolution screens.
* **CSS Art**: Hearts were created using single `div` elements and complex `box-shadow` properties to draw each pixel.
* **Animations**: Utilized `@keyframes` for the heartbeat pulse and the floating mini-hearts.

---
Built with love for a special someone <333333
