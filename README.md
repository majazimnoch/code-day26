# To do list with Vue
## Intro
This is day 26 of my 30-day coding challenge. I use HTML, CSS and JavaScript.

## Idea
I wanted to practise more of JS functions, conditions and methods and building the tic tac toe game offers it all. The game is designed to be played in a web browser, and the code manipulates the Document Object Model (DOM) to handle user interactions and update the game state.

## Breaking down the code
The game initializes with an empty 3x3 grid and displays the current player's turn.
Event listeners are attached to each grid cell, and a restart button to handle user input.
The grid is represented by an array (options) with nine elements, initialized to empty strings.
Players are represented as "X" and "O," and the current player is initially set to "X."
When a player clicks on a cell, the `cellClicked` function is invoked.
If the selected cell is empty and the game is still running, the cell is updated with the current player's symbol ("X" or "O").
After each move, the game checks for a winner or a draw.
The game defines winning combinations (`winConditions`) that result in a player winning the round.
The code iterates through these conditions to check if any player has won.
If a player wins, the game declares the winner and stops further moves.
If the game ends in a draw, it announces a draw.
Otherwise, the turn switches to the next player.
The restart button resets the game state, allowing players to start a new round.

## Demo
Click <a href="https://thriving-hamster-649c61.netlify.app/">here</a>.