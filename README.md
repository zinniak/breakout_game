# SI507_Project4

**Project Option:** Option 2

**Name:** Zinnia Khan


## Project Description

The `basepong.py` file is a single-player game similar to the game *Breakout*. The objective is to break all the white bricks by moving the paddle up or down and deflecting the red ball towards the bricks.  The speed of the ball will increase by a small amount every time 10 bricks are broken in succession without letting the ball hit the left wall. If the ball hits the left wall, the game will pause and the speed of the ball will be reset.

## Added Feature

To increase the difficulty of the game, I programmed a second ball object to appear after 50 bricks have been broken (code added on `line 345`). The player will have to keep both the original ball and the second ball from touching the left wall. The second ball will have the same velocity as the initial velocity of the first ball.

## How to Run the Game

1. Run the command prompt and go into the directory that has the `basepong.py` file.
2. Once in the correct directory, run the program by typing the following in the command prompt: `python basepong.py`.
4. Control the panel on the left by pressing the `W` key to move up and the `S` key to move down.
3. The game will begin running. The game can be paused by pressing `P`, reset by pressing `R`, and exited out of by pressing `Q`.
4. If the ball hits the left wall behind the paddle, the game will pause, hit `P` to resume.
