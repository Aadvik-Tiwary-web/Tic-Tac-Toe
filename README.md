# Tic-Tac-Toe
<br />
What Is Tic-Tac-Toe?
1. Tic-Tac-Toe is a classic two-player game played on a 3×3 grid. Players take turns placing their symbols—X or O—in empty squares
2. The goal is to be the first to align three of your symbols in a row—horizontally, vertically, or diagonally
3. If all squares are filled without achieving this, the game ends in a draw

Strategy & Optimal Play
Tic-Tac-Toe is a solved game—if both players play optimally, the outcome will always be a draw

Optimal Move Priorities:
According to a proven framework, on each turn:
1. Win – If you have two in a row, place the third to win.
2. Block – If your opponent has two in a row, block them.
3. Fork – Create a situation with two simultaneous threats (two ways to win).
4. Block Opponent’s Fork – Prevent your opponent from creating a fork.
5. Center – If open, take the center square.
6. Opposite Corner – If they’ve taken a corner, take the opposite one.
7. Empty Corner – Occupy an empty corner if available.
8. Empty Side – Finally, take a side square
