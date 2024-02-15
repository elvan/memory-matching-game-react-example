# Memory Matching Game

![Screenshot](https://raw.githubusercontent.com/elvan/memory-matching-game-react-example/main/_screenshots_/Screenshot%202024-02-15%20215142.png)

## Description

This project is a memory matching game developed using React. It challenges players to match pairs of cards by remembering their locations. The game is designed to improve cognitive skills and memory. It provides an engaging way to test and enhance quick thinking, memory, and attention to detail through a simple yet captivating interface.

## Features

- **Dynamic Card Shuffling** - Utilizes a random sorting algorithm to shuffle cards at the beginning of each game, ensuring a unique experience every time.
- **Card Flip Animation** - Implements CSS-based animations for flipping cards, enhancing the user experience with visual feedback during gameplay.
- **Match Detection** - Automatically detects when two cards match and keeps them flipped, reinforcing the memory aspect of the game.
- **Turn Counter** - Tracks the number of turns taken, allowing players to measure their performance and improve over time.
- **Automatic Game Initialization** - Starts a new game automatically upon loading the application, ensuring a seamless start to the game without additional input required from the player.

#### Technology Stack

- React (Hooks and functional components for state management and lifecycle events)
- CSS for styling and animations
- HTML for structure

## Installation

### Prerequisites

- Node.js and npm (Node Package Manager)
- A modern web browser

### Environment Setup

1. **Clone the repository:**

```bash
git clone https://github.com/elvan/memory-matching-game-react-example.git
```

2. **Navigate to the project directory:**

```bash
cd memory-matching-game-react-example
```

3. **Install dependencies:**

```bash
npm install
```

## Usage

To run the game locally after installation:

1. **Start the development server:**

```bash
npm start
```

2. **Open your web browser and navigate to:** `http://localhost:3000`

The game should now be running and accessible for play. Click on the cards to flip them and try to match pairs with the least number of turns possible. Press "New Game" at any time to reset the game board and start a new challenge.
