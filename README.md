# GAME 2048 #

[Link](https://boryskerekesha.github.io/game_2048/)

***
### Used technologies: ###

  * HTML5
  * CSS3
  * JS

***
### Game Logic ###

- The game field is 4 x 4 (16 cells), but it can be easily changed to any size in code
- Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
- The game starts with 2 cells filled with 2 or 4
- The game can be started by clicking the `Start` button
- The player can move cells with keyboard arrows
- All the numbers are moved in the selected direction until all empty cells are filled in
   - 2 equal cells are merged into a doubled number
   - The merged cell can't be merged twice during one move
- The move is possible if at least one cell is changed after the move
- After move 2 or 4 appears in a random empty cell. 4 probability is 10%
- When `2048` value is displayed in any cell, win message will be shown.
- The `game over` message will be shown if there are no more available moves.
- Score is increased by the sum of all merged cells.
- High score is saved in local storage.
- The game can be restarted by clicking the `Restart` button.

### About Project ###

The aim of this project is to combine JavaScript(DOM), HTML and CSS. My version of the game uses only Vanilla JS, without any libraries. Please don't play for long :)

***
