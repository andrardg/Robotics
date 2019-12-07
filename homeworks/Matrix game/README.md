Flappy bird

The game is a side-scroller where the player controls a bird, attempting to fly between columns of pipes without hitting them. I have chosen to create this game because I find that playing it is equally difficult and addicting. I will be using:
- LCD for the menu
- 8x8 LED matrix for the game itself
- MAX7219 Driver, connected to the matrix
- Joystick, both for playing and for going through the menu
- Buzzer, that plays a sound when you either win or lose and a song in the rest of the time
- 4 digit 7 segment display for the highscore
- EEPROM for saving the highscores

The menu has the following options:
- Play Game
- Highscore
- Settings
- Info

In the highscore page, you can see the top 3 highscores and the names of the players. The score increases by 1 point after each colomn is passed. After the game, if a new highscore has been obtained, you enter the name through the LCD.

In the Settings page, you have the option of choosing the starting level, which increases the speed of the coloms. Also, you can set the volume of the buzzer.

In the Info page, there is information about the creator's name, the game's name, the github link and the name of the robotics club, which you can scroll through.

While you are in the menu, there is a Christmass animation on the matrix.

HOW TO PLAY
After you choose Play Game, you have 3 seconds before the colums start coming. There is only one column at a time on the matrix, coming from right to left. The bird is constantly on the left side and you have to press the button on the joystick to make it rise from the ground. The bird falls very quickly, so you have to press the button relatively often. Each colum has either a 2 or a 3 spaces gap, which the bird has to go through. If you touch the colums, you lose a life. In total, there are 3 lives. You can only win the game by reaching level 1000.
