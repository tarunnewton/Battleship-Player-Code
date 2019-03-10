Battleship
==========

The game
--------

Long version: [see wikipedia](https://secure.wikimedia.org/wikipedia/en/wiki/Battleship_game)

* Each player starts with a fleet of 5 ships, of length 5, 4, 3, 3, and 2.
* Each player places their ships horizontally or vertically on a 10x10 grid;
  this is not visible to their opponent.
* Players take turns to fire at positions on the grid, gradually revealing
  where their opponent’s ships are and are not located.
* A ship is destroyed when every cell of a ship has been hit.
* The winner is the first player to destroy their opponent’s fleet.

You lose if:

* You do not place the correct number and size of ships.
* You place your fleet in impossible positions (ships overlapping or partly off
  the board).
* Your code raises an exception.
* All your ships have been sunk.

Implementation
--------------

Play takes place on a 10x10 grid. Co-ordinates are given in the order _(x,y)_
and are zero-indexed relative to the top left, i.e. _(0,0)_ is the top left,
_(9,0)_ is the top right, and _(9,9)_ is the bottom right.
