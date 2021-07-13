# Ultimate Tic-Tac-Toe Game
A full stack web app using React as front-end. Ultimate Tic-tac-toe consists of 9 regular Tic-tac-toe boards, which can each be thought of as 9 different entire squares. You now need to win each of the smaller boards first until there is a line of three.

Simple Rules
Rule 1: In each turn, you can mark any of the small squares on a board.
Rule 2: If you get three in a row on a small board, that board is won by you (same rules as normal TTT).
Rule 3: To win the entire UTTT game, you must win three small boards in a row.

New Rules
Rule 1: A player can only place a mark on the board decided by the position of your opponent's last placed mark. This means that if the opponent places an X or O in the bottom left corner of a square, the next player must make their move on that board. Therefore, you cannot pick what board to play on: the opponent's previous move determines which board you will play on. For example, if the opponent picks square 5, you will play on board 5.

Rule 2: The opponent can force you to choose an open square in an already won or tied board.

Rule 3: If a given board is filled, you get to choose a mark on any other board.

Resources:
https://mathwithbaddrawings.com/ultimate-tic-tac-toe-original-post/
https://mathwithbaddrawings.com/2013/11/18/tic-tac-toe-puzzles-and-the-difference-between-a-puzzle-and-a-game/
