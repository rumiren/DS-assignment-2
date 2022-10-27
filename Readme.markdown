# DS assignment 2

In this assignment, I program for the shogi.

## What will show you when run this code
#### 1. For starting a new game
1. In the beginnig, the initial chess board will be printed. 
2. It will tell you whose turn is it, then ask you whether you want to save.
3. It will ask you the chess's position you want to moved and where to move.
4. You can enter '0' to regret when step 3 occur.
5. Renew the chess board and show the time you spend.
6. Enjoy the game!
#### 2. For loading a old game
1. In the beginnig, the initial chess board will be printed.
2. You can enter 'f' for the next step or 'b' for the previous step.

## Compile & Run

```sh
# Compile
gcc -o main HM1.c -lev
# Run for starting a new game
./main -n -s saved_filename
//saved_filename should be in 20 leters and use '.txt'.
# Run for loading a old game
./main -l loaded_filename
```
