# Minesweeper

## Game rules

- the game starts when the player left clicks on a square
- the first click is always safe and reveals a number or opening surrounded by numbers
- each number tells the player how many mines are in the 8 adjacent squares
- right mouse button will mark squares as mines by displaying a flag on them
- if all the mines are flagged around a number you can press both mouse buttons to clear the adjacent squares
- __Win__ - clear all the safe squares
- __Lose__ - left mouse click on a mine
- _Mine counter (top left)_ - mines left
- _Status icon (top middle)_
    - Happy - idle
    - Surprised - square is clicked but not released yet
    - Sad - game over
    - Like a boss - game won
- _Time counter (top right)_ - score 
- Dificulty levels:
    - Beginner - 10 mines (grid 9x9)
    - Intermediate - 40 mines (grid 16x16)
    - Expert - 99 mines (grid 16x30)
    - Custom - player inputs the number of mines
- maximum grid size is 24x30 (subject to change)
- maximum mines (X - 1)(Y - 1)