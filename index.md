## Magic 2048 Help Page

# How To Play:

Magic 2048 is very similar to the original 2048 game. The goal of this game is to get the final 2048 block with the addition of **"Magic Items"** in the game that will help the user get the final 2048 easier with more fun.

The user can use either WASD or the arrow keys to move the tiles.

# Tokens:

Tokens is the currency of the game that is rewarded to the user based on their progression in the game. 
The amount that is given every game is based on this formula: Progression% * 100 = Tokens.

# Magic Items:

Magic Items are powerful items that can be purchased using tokens in the shop. However, using Magic Items will increase the # of moves of the user depending on the ablity of the Magic item

| Magic Item      | Description |  Cost in Tokens   | Increase in steps|
|  ----        |    ----   |      ---- | ---- |
| The Lightning   | Remove A Tile Instantly | 10   |  25 |
| Book Of Double  | Double A Tile's Value     | 30    | Doubled tile/2 |
| Control Z  | Undo The Last Step   | 15    | 40 |

# Game Tips:

## 1. Keep your tile with the highest value in one corner of the whole game.

## 2. Keep your highest value tiles lined-up.

![Game Grid](/assets/Magic2048.jpg)
For example, I keep my highest value tiles in one column.

## 3. Keep the tiles occupied

## 4. Use the Magic Items when necessary!

# Leaderboard:



# FAQs:

### Lose Focus Problem: 

There is a chance that the gamegrid will lose its focus during gameplay, the program itself request refocus everytime when other buttons on the frame is being clicked. You can use your mouse to click on the game grid to reset its focus.

### Why does my move count increase when I press a direction and the gamegrid does not move?

In the algorithm, the movecount depends on the user Keyboard input and when the gamegrid does not move, it will count as moves since the user is still trying to move by pressing the keyboard.
