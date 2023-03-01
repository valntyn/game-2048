# 2048 game [DEMO LINK](https://valntyn.github.io/game-2048/)

### Game logic

1) The game field is 4 x 4
2) Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3) The player can move cells with keyboard arrows
4) All the numbers should be moved in the selected direction until all empty cells are filled in
   - 2 equal cells should be merged into a doubled number
   - The merged cell can’t be merged twice during one move
5) The move is possible if at least one cell is changed after the move
6) After move 2 or 4 appears in a random empty cell. 4 probability is 10%
7) When 2048 value is displayed in any cell, win message will be shown.
8) The `game over` message will be shown if there are no more available moves.
9) Start message will be hidden when game starts.
10) Changed the `Start` button to `Restart` after the first move.
11) Increased score with each move.


![Preview](./src/images/reference.png)

### This project is inspired by original [2048 game](https://play2048.co/)
