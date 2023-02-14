# Tic-Tac-Toe-AI

## Basic Info

This Tic Tac Toe AI is made using the Minimax algorithm, serving the purpose to train another AI (neural networks)

You may find the other AI in [this link](https://github.com/pleituer/neuralNet/tree/main/examples/Tic%20Tac%20Toe)

## How to use

It's simple, with one command:
```
~$ python3 ticTacToePlay.py
```
Then follow the instructions, enter format is: `> {column} {row}`

For example, entering `2 1` will mean your desired spot is column 2, row 1. Both row and column starts counting from 0, so `0 0` will mean the top left corner, `2 0` will mean the top right corner.

Also, `X` means going first and `O` means second. You may change whether the bot should go first or second by setting the variable `TRAINSIDE` to be `X` or `O` respectively
