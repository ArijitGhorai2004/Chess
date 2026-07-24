# Flask Chess Engine

This is a simple chess engine and web interface created using Flask. The application utilizes chessboard.js and chess.js for the logic of the frontend chessboard, while relying on python-chess for the logic of the backend chessboard. All engine calculations are executed on the backend using Python.

## Features

*   **Interactive Web Interface:** A playable browser-based chessboard served via Flask.
*   **Custom Chess Engine:** A backend engine built from scratch in Python.
*   **Advanced Search Algorithms:** Utilizes the Minimax algorithm enhanced with Alpha-Beta pruning to find optimal moves.
*   **Iterative Deepening:** Calculates moves progressively to manage search depths effectively.
*   **Position Evaluation:** Evaluates board states using material counting and piece-square tables for strategic positioning.

---

## Prerequisites and Installation

To run this application on your local machine, you must install Flask and the python-chess library. 

Open your terminal or command prompt and install the dependencies using Python's module flag to avoid execution policy errors:

1. Install Flask:
   `python -m pip install flask`
2. Install Python Chess (with UCI and Gaviota tablebase support):
   `python -m pip install python-chess[uci,gaviota]`

---

## Usage

Once the dependencies are installed, you can start the local web server by executing the main Flask application script. 

Run the following command in your project directory:

`python flask_app.py`

After the server starts, open your web browser and navigate to `http://127.0.0.1:5000/` (or the address provided in your terminal) to view the interface and play against the engine.

---

## Project Structure

| File | Description |
| :--- | :--- |
| **`flask_app.py`** | The main web server file that handles routing, serves the `index.html` template, and requests moves from the engine. |
| **`chess_engine.py`** | Contains the `Engine` class, which handles board evaluation, material scoring, and algorithmic search (Minimax, Alpha-Beta, Iterative Deepening). |
| **`board_test.py`** | A testing script used to initialize a board, print legal moves, and test standard algebraic notation (SAN) moves. |
| **`.gitignore`** | Specifies intentionally untracked files to ignore (e.g., compiled source files, logs, OS generated files like `.DS_Store`, and editor configurations). |
| **`readme.txt`** | The original text file containing basic installation instructions and a brief overview of the tech stack. |