# WordWhiz

A hangman-style word game built with plain HTML, CSS and JavaScript. Each round picks a random word and shows a hint, and you guess letters on an on-screen keyboard before the hangman drawing is finished.

**Live demo:** https://melissabuie.github.io/WordWhiz/

<!-- Add a screenshot: save one as images/screenshot.png and uncomment the next line -->
<!-- ![WordWhiz screenshot](images/screenshot.png) -->

## Features

- Random word with a hint each round, from a list of 20+ words
- On-screen A to Z keyboard built with JavaScript
- Hangman drawing updates after each wrong guess (6 tries)
- Win and lose screens with a Play Again button

## Built with

- HTML5
- CSS3
- JavaScript (DOM manipulation, event listeners, no libraries)

## What I learned

- Building UI elements (the keyboard) from JavaScript instead of hard-coding them
- Keeping game state (current word, correct letters, wrong guesses) in variables and resetting it cleanly
- Swapping images and showing a modal based on that state

## Run it locally

Clone the repo and open `index.html` in your browser. No install needed.

```bash
git clone https://github.com/MelissaBuie/WordWhiz.git
cd WordWhiz
open index.html   # or double-click the file
```
