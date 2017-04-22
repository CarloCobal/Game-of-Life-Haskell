# Game-of-Life-Haskell
Implementation of Game of Life in Haskell

# Description
The game models simple evolutionary system based on cells, and is played on a two-dimensional board. Each square on the board is either empty, or contains a single living cell, as illustrated in the following example:

```
||==========================||
||   |   |   |   |   |   |  ||
||--------------------------||
||   |   |   | 0 |   |   |  ||
||--------------------------||
||   |   |   | 0 | 0 | 0 |  ||
||--------------------------||
||   |   |   |   | 0 |   |  ||
||--------------------------||
||   |   |   |   |   | 0 |  ||
||==========================||
```

# Rules
Given an initial configuration of the board, the next generation if the board is given by simultaneously applying the following rules:
- a living cell survives if it has precisely 2 or 3 neighbouring squares that contain living cells, and
- an empty square gives birth to a living cell if it has precisely 3 neighbours that contain living cells, and remains empty otherwise.

# Game Demo
![Game Demo](https://github.com/rst0git/Game-of-Life-Haskell/raw/master/GameOfLife.gif)

# Reference
The materials were gathered from the book "Programming in Haskell" http://www.cs.nott.ac.uk/~pszgmh/pih.html
