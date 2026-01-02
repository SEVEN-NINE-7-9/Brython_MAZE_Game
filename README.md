## Voice Maze

A Voice-Controlled Maze Game built with Brython + Web Speech API

Voice Maze is an interactive browser-based maze game where players navigate a procedurally generated maze using voice commands or keyboard controls. Built with Brython (Python in the browser) and the Web Speech API, the game demonstrates how Python, JavaScript, and modern web APIs can work together to create engaging, accessible gameplay.

## Gameplay Overview

Navigate through a 25×25 randomly generated maze

Collect all coins placed throughout the maze

Reach the exit (green tile) after collecting every coin

Control the player using:

## Voice commands (primary mode)

## Keyboard input (fallback)
## Voice Commands Supported

The game recognizes natural speech patterns such as:

up, down, left, right

go up, move left, go right

Directional words like north, south

Recognized speech is displayed in the log panel for clarity and debugging.

Recommended browser: Chrome or Edge (desktop)
Voice recognition is not supported in all browsers.

## Keyboard Controls
Key	Action
Arrow Keys	Move player
W A S D	Move player

Keyboard controls work even when voice control is disabled.

## Technical Features

Brython (Python 3.12) running directly in the browser

Perfect Maze Generation using DFS backtracking

Canvas-based rendering for smooth visuals

Web Speech API integration for real-time voice commands

Game timer & move counter

Dynamic coin placement

Responsive UI for smaller screens

## Technologies Used

HTML5 & CSS3

JavaScript

Brython

HTML Canvas API

Web Speech API

## How to Run

Download or clone the repository

Open the index.html file in Chrome or Edge

Allow microphone access

Click Play (voice) and start speaking commands!

No server or installation required — runs fully in the browser.

##  Game Mechanics

Start position: Top-left corner (blue)

Player: Yellow

Coins: Gold

Exit: Green

Walls are procedurally generated and guaranteed to be solvable

Timer starts when a new maze is generated

## Future Enhancements (Ideas)

Difficulty levels (larger mazes, more coins)

Mobile-friendly voice support

Sound effects and animations

Leaderboard with best times

Accessibility improvements for speech feedback

## License

This project is open-source and intended for learning, experimentation, and demonstration purposes.