LIVE DEMO LINK :- https://rubik-s-cube-solver-rose.vercel.app/

About The Project
This project provides a fully functional 2D representation of a Rubik's Cube. Users can generate a scrambled cube, watch the application find a solution, and apply manual rotations. The interface is designed to be clean and intuitive, with a responsive layout that works on both desktop and mobile devices.
The primary goal of this project was to implement the core mechanics of a Rubik's Cube and create a visual interface for interaction, all without relying on any external frameworks or libraries.
Disclaimer: The current solving algorithm is a simple, non-optimal "random walk" solver designed for demonstration purposes. It will find a solution but not necessarily the shortest one.
Features
Interactive Cube: A 2D "unfolded" view of the cube that updates in real-time.
Scramble Function: Generate a random, solvable scrambled cube with a single click.
Auto-Solver: Watch the application solve the cube and display the moves.
Step-by-Step Solution: The solution moves are displayed in a responsive grid, making them easy to follow without excessive scrolling.
Manual Controls: Apply all standard clockwise (e.g., U, R, F) and counter-clockwise (e.g., U', R', F') moves using on-screen buttons.
Status Indicator: A clear message indicates whether the cube is currently solved or unsolved.
Responsive Design: The layout adapts smoothly from large desktop screens to smaller mobile devices.
Pure Vanilla JS: No frameworks or dependencies. Just plain HTML, CSS, and JavaScript.
How to Use
Scramble: Click the "Scramble Cube" button to generate a new puzzle.
Solve: Click the "Solve Cube" button. The solver will run, and the solution steps will appear in the right-hand panel (or below the cube on smaller screens).
Manual Moves: Use the U, D, R, L, F, B and U', D', R', L', F', B' buttons to rotate the faces manually.
Reset: Click the "Reset to Solved" button to return the cube to its initial, solved state.
