# Self-Learning Chess AI

This project is a Gradio-based web application that allows users to play a game of chess against an AI. The AI agent uses Monte Carlo Tree Search (MCTS) to simulate and determine optimal moves in response to user input. The current board state is displayed visually, updated after each move.

## Features

- **Play Against AI**: Users can make moves using standard algebraic notation, and the AI will respond with its own move.
- **Real-time Board Visualization**: Displays the chess board with the current positions of pieces after each move, updated dynamically.
- **Move Validation**: Validates user moves and provides feedback on invalid inputs.

## Installation

To run this application, ensure you have Python installed, along with the following libraries:

- `gradio`
- `python-chess`
- `cairosvg`
- `Pillow`

Install these dependencies via pip:

```bash
pip install gradio python-chess cairosvg Pillow
