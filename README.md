# Mapello 

A graphical interface for the Mapello game, using JavaScript and WebGL.

![](/src/images/LAIG3_T01_G03_4.png) | ![](/src/images/LAIG3_T01_G03_3.png) |
|----|----|

A project developed by [Diana Freitas](https://github.com/dianaamfr) and [Eduardo Brito](https://github.com/edurbrito).
*LAIG, MIEIC, FEUP, 2020/2021.*

*The game was developed using Prolog for PLOG course and adapted for this project. The full Prolog game can be consulted [here](https://github.com/dianaamfr/PLOG_FEUP-Mapello).*

## Instructions

- Open `prolog` directory. Consult `server.pl` in SICStus Prolog and execute the predicate `server`.
- Open your browser and select the game configuration in the main menu.
- Start the game by pressing `play`.

![](/src/images/plog.png) | ![](/src/images/LAIG3_T01_G03_1.png) |
|----|----|

## Commands
* The player has 60 seconds to play.
* To play, the player indicated on the scoreboard can choose any piece of the left auxiliar board by clicking on it.
* After choosing a piece, the valid moves will be shown.
* To play, the user must click in a valid cell.
* The player wins 3 points if he selects a cell with a power-up.
* When none of the players can make a valid move, the total points are calculated and the winner is shown on the scoreboard.

## Interface

On the top right of the screen, after pressing the `play` button, the user can change the camera, the scene and also the lights. 
*Undo* and *Replay* are also available during the whole game.

## Rules
Mapello is a two player game played with Reversi black and white pieces. The Board, with a 10x10 configuration, is delimited by walls, leaving an inner 8x8 playable area.  Two pieces of each player are initially placed in the center cells, in a diagonal pattern. 

This game also adds extra pieces to the traditional Reversi game: walls, power-ups and jokers.
'Walls and power-ups can be placed anywhere on the inner 8x8 area (except on the four centre squares), and jokers can be placed anywhere on the outer 10x10 border.' 

The players alternate turns and the black player always plays first. In each move, the player must place a piece in an empty cell or in a cell with a power-up that is adjacent to a piece of the opponent. 
'All the opponent's pieces that are trapped in a contiguous straight line (either diagonal, vertical, or horizontal) between the newly placed piece and an existing piece of that colour, or a joker, are flipped over to the player's colour. A legal move must case at least one opponent piece to be flipped. If a player cannot make a legal move then they pass.'

The game ends when none of the players has valid moves. The number of pieces of each player on the board are added to the power-up points. The winner is the player with more points.

> [For detailed instructions click here to consult the original font.](https://boardgamegeek.com/boardgame/131567/mapello)

